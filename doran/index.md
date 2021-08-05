# 소개

## github 가이드라인

### Branch 소개

도란도란 서비스는 Git-flow로 브랜치를 관리하고 있습니다. ([우아한 형제들](https://techblog.woowahan.com/2553/)) ([강남언니](https://blog.gangnamunni.com/post/understanding_git_flow/))

본 프로젝트의 브랜치 구성은 아래와 같습니다.
- master: 실제 배포되는 버전으로 해당 브랜치에 push 시 자동으로 CI/CD 과정을 거쳐 배포가 진행됩니다.
- develop: 개발 과정에서 사용되는 브랜치로 해당 브랜치에서 기능 추가 및 테스팅을 진행합니다.
- feature branches: `develop/voice` 와 같은 형식으로 develop 브랜치에서 분기하여 특정 기능을 개발합니다.

### Commit Message

![Commit 예시](https://user-images.githubusercontent.com/45455072/128326228-97ac8d03-968f-4742-be31-a80597b611a9.png)


Commit Message 구조
```
[type]: 수정 된 내용
```

**Type**

- feat: 새로운 기능 추가
- fix: 버그 수정
- style: 코드 스타일 혹은 포맷 변경
- docs: 문서 수정
- chore: 이 외 간단한 수정
- test: 테스트 코드 추가 및 수정
- refactor: 코드 리팩토링

### Pull Request

TODO: 작업 하면서 추가