git 글로벌 설정을 에디터로 설정

```bash
git config --global -e
```

```bash
[user]
    name = USER_NAME
    email = USER_EMAIL

[alias]
    gr = og --graph --abbrev-commit --decorate --format=format:'%C(cyan)%h%C(reset) - %C(green)(%ar)%C(reset) %C(white)%s%C(reset) %C(dim white)- %an%C(reset)%C(yellow)%d%C(reset)' --all
```
