# Final projects Stat 585 - time travelling!

For the final project you are asked to work in a team with 3-5 members. 
Each team is asked to create an R package. You are free to choose package functionality, but there should be

- a minimum of five functions with a coherent theme,
- a shiny app show-casing some of the functionality
- a website for the package
- a README page with installation instructions and basic demonstration of functionality
- evidence of testing the functionality (e.g. show the code coverage)
- 8-10 page report detailing your work. This report should be written as a package vignette, included in your package's documentation.  

You are asked to present your work as a team in one of the speaking slots during dead week and finals' week. Each team member is supposed to present for about 5 mins. 


Stage 1 (Mar 27): Identify team and topic

Stage 2 (Apr 10): Functional Package

Stage 3 (Apr 24): Testing and Documentation 

Stage 4: Presentation (Dead week and Finals)

Stage 5 (May 9th): Package submission to canvas (Finals week)




## Grading Rubric:

### Package (40 points)

Criteria  | Outstanding (> 90%) | Good (70-90%)     | Needs work (50-70%) | Needs a lot of work (< 50%) |
--------- | ----------- | --------- | ---------- | ------------------- |
Package Topic | Package is useful and coherent, addressing a well-defined problem. | Package is useful, but may have some implementation gaps or lack a coherent solution to the main problem the package addresses | Package is incoherent, including functions not aimed at addressing the stated issue | Package does not address a single problem or consists of seemingly random functions | 
10 points |             |           |            |                     |
Builds and Installs | Package builds and installs correctly. | Package builds and installs correctly with only minor modifications. | Package builds and installs correctly with major modifications. | Package does not build and install correctly during the grading process. |
5 points |             |           |            |                     |
Documentation | Each exported function is well documented, with examples detailing its use. Package uses `pkgdown` to present documentation to the reader. | Most functions are well documented, but gaps in examples or full documentation exist. Documentation on `pkgdown` exists, but may have some deficiencies or be slightly out of date. | Some functions are documented, but large gaps in documentation and examples exist, making it difficult to understand how to use the package functions. Package documentation may exist, but `pkgdown` is not used to make the documentation easily available on the web. | The package is poorly documented, or existing documentation is not easy to read and understand. No attempt to use `pkgdown` to make documentation available online. |
5 points |             |           |            |                     |
Testing | Package has over 90% test coverage with meaningful tests. Functions are structured to do only one thing to make testing efficient. Package integrated with TravisCI and Codecov.io, and test coverage and status are reported in the package README. | Package has over 80% test coverage. Tests cover some important functionality but unnecessary tests exist and/or tests miss important areas of coverage. Functions may not be written to perform only one task. Travis integration and Codecov.io integration are set up but may not be working consistently. | Package has less than 80% test coverage with meaningful tests. Functions are not well structured for testing. Travis CI or Codecov.io integration is not working. | Package has minimal or no useful testing. No attempt to make use of Travis CI or Codecov.io to show package testing status. |
5 points |             |           |            |                     |
Package Data | Package includes some data which is useful for demonstrating the package functions. Data is well documented and used in the examples and the package vignette. | Package includes data used to demonstrate the package, but documentation is lacking and/or the data is not integrated into examples and the package vignette. Package may include some data which is not properly documented or necessary to the package's functions | Package includes data but it is not well documented. Examples and vignettes may use data which is not included in the package and is also not explained or documented well. | Package does not include data or includes data with no documentation or explanation |
5 points |             |           |            |                     |
Spelling | Package and documentation is spell-checked | Some spelling errors are present but writing is mostly coherent | Package documentation and function comments have noticable lapses in spelling and/or grammar. | Package documentation is poorly spell-checked, has incomprehensible grammar, or is non-existent |
5 points |             |           |            |                     |
Dependencies/Imports | Package has dependencies and imports that make sense | Package has a few extra imported packages, or packages which are listed as dependencies that could be imported instead | Package is missing imports or dependencies | No attempt has been made to list imports and dependencies in a coherent fashion |
3 points |             |           |            |                     |
Exported functions | Only functions which are intended to be shown to the user are exported; all exported functions have examples and supporting documentation | Some attention has been given to only exporting functions intended for user use, but there are some issues with the implementation | All functions are exported, or functions that are intended for user use have not been exported | No attention has been paid to which functions should be imported or exported |
2 points |             |           |            |                     |

## Shiny App (30 Points)

Criteria  | Outstanding (> 90%) | Good (70-90%)     | Needs work (50-70%) | Needs a lot of work (< 50%) |
--------- | ----------- | --------- | ---------- | ------------------- |
Installation | Installation instructions are complete, shinyApp loads and runs without problems | minor things have to be taken care of before the app runs or installation instructions are missing crucial information | minor things have to be taken care of before the app runs and installation instructions are missing crucial information |  major steps need to be taken to ensure that the app runs, installation instructions are missing or not helpful |
10 points |             |           |            |                     |
Functionality  | The shiny app provides access to an important piece of the package and works smoothly.  | | | The app  demonstrates a minor aspect of the package. The app stops working intermittently. |
10 points |             |           |            |                     |
Complexity |  Multiple interactive UI elements are implemented  | | | The app is quite simplistic. |
10 points |             |           |            |                     |

## Vignette (30 Points)

Criteria  | Outstanding (> 90%) | Good (70-90%)     | Needs work (50-70%) | Needs a lot of work (< 50%) |
--------- | ----------- | --------- | ---------- | ------------------- |
Uses `pkgdown` and github /docs | Report is formatted as a vignette using `pkgdown` and integrated into the github repository using the /docs folder. | Report can be generated reproducibly and is located in the /docs folder, but does not use `pkgdown` or is not connected to the package's github.io site | Report is not reproducible or not located in the correct location | Report consists of loosely connected pieces | 
8 points |             |           |            |                     |
Content | Report describes the use of the package and package functions, unifying the separate functions included in the package to solve a single problem or task. Each major function is included in the vignette, with substantial additional text explaining the use of the function to solve a real-world problem. | Report describes the use of the package and package functions, but does not present the package as a unified entity aimed at a specific single task. Some descriptions are sparse; the vignette may leave the reader with additional questions that are not completely answered. Code examples may only cover specific use cases instead of a more general approach | Vignette does not include all major functions, examples do not demonstrate major package functionality, and additional textual descriptions may be sparse or absent in places. | Vignette does not demonstrate major package functionality, and only includes minimal text description of the package's capabilities. |
7 points |             |           |            |                     |
Graphs and Tables | Graphs and tables included in the package vignette are designed for a specific purpose and are carefully constructed to communicate with the reader. Each graph or table illustrates one point or package feature. Formatting and styling show that some optimization and care went into the creation of the table or graph | Graphs and tables are well constructed but may have minor flaws or poor labeling decisions. | Many graphs or tables have minor problems, or may be poorly chosen or redundant. | Graphs and tables do not support questions and findings. Major problems with presentation - graphs may be missing or fail to generate. |
10 points |             |           |            |                     |
Text | English is polished, concise, and clear. No grammar or spelling mistakes | Clear and concise, but not elegant. Some spelling/grammar errors | Readable, but unnecessarily verbose or lacking in detail. Many errors that compromise readability. | Barely readable, with many spelling and grammar errors. No evidence of any proof-reading. |
5 points |             |           |            |                     |
