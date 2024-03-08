# Rubocop
Rubocop for rails projects

## Setup
Insert the subsequent line into the `.rubocop.yml` file of the project. Ensure it resides under the inherit_from section.
```
inherit_from:
  - https://raw.githubusercontent.com/Sentia/rubocop/`<version>`/.rubocop-sentia.yml
```
Replace the `<version>` with your chosen version.

## Illustration
```
# .rubocop.yml
inherit_from:
  - https://raw.githubusercontent.com/Sentia/rubocop/v1/.rubocop-sentia.yml
  - .rubocop_todo.yml
```