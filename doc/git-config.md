# Comandos git e alias

```sh
# Abrindo arquivo de config do git
git config --edit --global
```

```sh
[user]
    name = Thiago Martins de Freitas
    username = martins86
    email = martins86@gmail.com
[init]
    defaultBranch = master
[credential]
	helper = wincred
[core]
    editor = code --wait
[alias]
    ## git s ( status mais limpo )
    s = !git status -s
    ## git c "msg" ( adiciona tudo e faz o commit )
    c = !git add . && git commit -m
    ## git amend ( adiciona no commit anterior )
    amend = !git add . && git commit --amend --no-edit
    ## git l ( log mais limpo )
    l = !git log --pretty=format:'%C(blue)%h%C(red)%d %C(white)%s %C(cyan)[%cn] %C(green)%cr'
```
<br>

---

<br>

<br>
<br>

[⬆ Voltar ao topo](#comandos-git-e-alias)<br>
