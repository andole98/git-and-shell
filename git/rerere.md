### REuse REcored REsolution

충돌상황을 해결한 것을 기록했다가, 다음에 자동으로 적용할 수 있다.   
리베이스 과정 중 충돌이 많이 발생할 때, 우선 merge와 rerere로 충돌 해결을 기록하고 rebase하면 한번에 충돌을 해결할 수 있다.

git rerere [command] [option]

```bash
git config --global rerere.enabled true
```

충돌 해결 과정에서 `.git/rr-cache` 디렉토리가 생기는지 확인.  
`Recorded preimage for [SOME_FILE]` 로그가 나오는지 확인.  
