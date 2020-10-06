# test
validando author do commit

validando committer do commit

validando author e committer do commit

# Comandos utilizados:
Alterando apenas o author:
```
git commit -m 'validando autor do commit' --author="Jose Pe de Chule <jose.chule@test.com>"
```

Alterando apenas o committer:
```
export GIT_COMMITTER_NAME="Jose Pe de Chule"; export GIT_COMMITTER_EMAIL="jose.chule@test.com"; git commit -m 'validando committer do commit'
```

Alterando o author e committer:
```
export GIT_COMMITTER_NAME="Jose Pe de Chule"; export GIT_COMMITTER_EMAIL="jose.chule@test.com"; git commit -m 'validando autor e committer do commit' --author="Jose Pe de Chule <jose.chule@test.com>"
```