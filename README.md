## Git Flow Study

### Init
```
git flow init
```

### Start
```
git flow feature start $(branch)
```

### Rebase
```
git rebase -i HEAD~{number}
```

#### Squash
- 이 명령어는 두개 또는 그이상 커밋을 단일 커밋으로 합칠 수 있다. 사용할 커밋을 선택한 뒤에 이전 커밋으로 수정된다.

#### Fixup
- squash와 비슷하지만 커밋메시지는 버려집니다. 커밋은 간단히 이전 커밋에 병합되고 첫번째 커밋 메시지가 사용됩니다.

#### Reword
- pick과 유사하지만 rebase 진행을 일시 정지하고 커밋 메시지를 변경할 기회가 주어집니다. 커밋 내용은 변경되지 않습니다.
