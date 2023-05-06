# Git Commit Message Template

## Commit Message Tags

- `feature` : New Feature or Functionality into the system
- `fix` : Bug or Error Fix in the system
- `documentation` : Changes to the Documentation (`.md`) File(s)
- `style` : Addition / Changes to Design Styles of the Application UI / UX
- `refactor` : Code Refactoring (Variable Renaming / Code Restructuring) that doesn't affect Functionality
- `test` : Adding, Fixing or Refactoring Tests; No Production Code Change
- `chore` : Updating Build Scripts / Upgrading Dependencies; No Production Code Change
- `devEx` : Developers' Experience : Use for anything that helps to improve developers' experience
- `miscellaneous` : Use for anything that does not clearly fall into any of the previous categories

## Examples

**General Commit Message**

```sh
git commit -m "documentation : Updated README File"
```

## Making References

**Commit Message with reference of PR (Pull Request)**

```sh
git commit -m "feature : Created Functionality for Password Validation (!1234)"
```

**Commit Message with reference of Issue / Task**

```sh
git commit -m "style : Created Design CSS Styling for User Login Screen (#1234)"
```

**Commit Message in the past (if you forget to commit on that particular date in the past)**

```sh
git commit --date="1 day ago" -m "feature : Added Test ID Attribute to 404 Not Found Page"
```
