# whatsthisfor
cli for discovering what those mysterious config files do and where to find documentation on them

# Installation
```bash
# NOT AVAILABLE ON npmjs.com YET
npm i -g whatsthisfor
```

# Usage
`whatsthisfor [file-pattern] [-r|--recurse]`
```
$ cd projectdir

$ ls -a
.                 .git/                   .editor                  src/
..                .gitignore              .tern-project            package.json

$ whatsthisfor
.gitignore gitignore
  - summary            - specifies intentionally untracked files that Git should ignore
  - full documentation - https://git-scm.com/docs/gitignore
.editorconfig EditorConfig
  - summary            - simple coding style editor preferences
  - full documentation - https://github.com/editorconfig/editorconfig/wiki/EditorConfig-Properties
.tern-project TernJS
  - summary            - Javascript stand-alone code-analysis engine used with a code-editor-plugin
  - full documentation - http://ternjs.net/doc/manual.html
package.json NPM
  - summary            - nodejs project manifest
  - full documentation - https://docs.npmjs.com/files/package.json
```
