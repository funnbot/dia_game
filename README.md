# Game
# [Folder Structure](./docs/folder_structure.md)

# Contributing
## Configure EOL (Windows)
```bash
git config core.autocrlf false
git config core.eol lf
```
### Re-normalize existing files
```bash
git add --update --renormalize
```
### List files in working directory with CRLF
```bash
git ls-files --eol | grep "w/crlf"
```
### List committed files with CRLF
Don't want this to happen
```bash
git ls-files --eol | grep "i/crlf"
```
