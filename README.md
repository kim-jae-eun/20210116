## 20210116 TIL

### Git Interactive Rebase

커밋의 순서를 바꿀 수 있다. `git rebase -i <수정을 시작할 커밋의 이전 커밋>`를 사용하며 UI창으로 가져올(또는 순서를 바꿀) 커밋을 선택할 수 있다. 이때는 `pick`을 사용한다.

예시)

1. README.md 추가
2. a.txt 추가
3. b.txt 추가
4. c.txt 추가

그 이후 `git rebase -i Head~3`를 해보면



