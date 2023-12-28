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

### Code Review

### VS Code Plugin

### CODEOWNERS 

### SemVer
