# dhall-config-files
Dhall config file samples

###Commands
dhall-to-yaml <<< '[ ./dhall-config-files/educationalBooks.dhall ]' > dhall-config-files/output/educational_books.yaml

dhall-to-json --pretty <<< '[ ./dhall-config-files/educationalBooks.dhall ]' > dhall-config-files/output/educational_books.json
