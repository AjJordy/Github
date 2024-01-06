# Gitflow

### Git Flow

- `$ sudo apt-get install git-flow`: Install Git flow
- `$ git flow`: Init Git flow
- `$ git flow feature start <NAME>`: Creating a new feature
- `$ git flow feature finish <NAME>`: Feature to Develop 
- `$ git flow release start <VERSION>`: Create a new release
- `$ git flow release finish <VERSION>`: Release to Main
- `$ git flow hotfix start <VERSION>`: Create a new hotfix
- `$ git flow hotfix finish <VERSION>`: Hotfix to Develop and to Main

### Configurando GPG

- `$ gpg --list-secret-key --keyid-form LONG`: Lista as chaves gpg 
- `$ gpg --full-generate-key`: Gera uma chave gpg
- `$ gpg --armor --export <KEY_ID>`: Exportar a chave gerada
- `$ git config --global user.signingkey <KEY_ID>`: Configurando git 
- `$ export GPG_TTY=$(tty)`: Exportando varável de ambiente
- `$ git config --global commit.gpgsing true`: Definir padrão sempre assinar commit
- `$ git config --global tag.gpgsing true`: Definir padrão sempre assinar tag

### Pull requests / Templates for PR

```bash
mkdir .github
vim .github/PULL_REQUEST_TEMPLATE.md
```


### SemVer

Semantical versioning 
"1.2.3" 

- Major: 1 (Breaking changes)
- Minor: 2 (New features) 
- Patch: 3 (Fix and adjusts) 

### Conventional Commits

 ```
<type>[optional scope]: <description>

[optional body]

[optional footer(s)]
```

**type**: 
- fix
- feat
- BREAKING CHANGE
- docs
- build
- refactor

### Github Action 

Ref: https://docs.github.com/pt/actions/quickstart