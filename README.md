# dhall-config-files
Dhall config file samples

https://github.com/dhall-lang/dhall-lang/wiki/Getting-started%3A-Generate-JSON-or-YAML

### Commands

dhall-to-yaml <<< '[ ./dhall-config-files/educationalBooks.dhall ]' > dhall-config-files/output/educational_books.yaml

dhall-to-json --pretty <<< '[ ./dhall-config-files/educationalBooks.dhall ]' > dhall-config-files/output/educational_books.json

#### Infra System Dhall 

dhall-to-json --pretty <<< '[ ./dhall-config-files/infraSystems.dhall ]' > dhall-config-files/output/infra_systems.json

#### Some options to remember 

∧ - merging two records 
++ - String concatenation 
Optional - should be defined as null. However, you can omit it using --omitNull
let - expression to give the function a name and then use that name to apply the function to an argument
let - can be used to define a variable which can be referenced multiple times
Anonymous functions - λ(inputName : inputType) → output
--explain flag - To get full error message if dhall expression is rejected 
Imports are possible. So types can be saved in the separate files and imported into dhall file