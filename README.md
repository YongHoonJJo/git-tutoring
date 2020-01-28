# git-tutoring

### Git vs Github
Git is a revision controll system, a tool to manage your source code history.
Github is a hosting service for git repositories.

<br>
### Git CLI

git add 를 통해 한 번 stage area 에 올라간 file 은 이후 .gitginore 에 등록을해도 적용이 되지 않는다.
```
$ git rm --cached node_modules -r
```
위와 같이 제외를 시키고 싶은 file 을 지워야 적용 가능해진다.
