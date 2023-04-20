# pet_119_back_end

##version

### java : 11
### spring boot : 2.7.10

***

✏️ [상세 설명](https://github.com/Byeong-soo/pet_119_back/wiki/GIT-%EC%83%81%EC%84%B8-%EC%A0%84%EB%9E%B5)

### ✏️Branch명 전략

**GitLab-Flow**

- Feature
  - `feature/#issue_number/user_name`
- Development
  - `develop`
- Master
  - `master`

### ✏️commit 규칙

`[#issue_number] ** : commit_head`

```
feat : 새로운 기능에 대한 커밋
fix : 버그 수정에 대한 커밋
build : 빌드 관련 파일 수정에 대한 커밋
chore : 그 외 자잘한 수정에 대한 커밋
ci : CI관련 설정 수정에 대한 커밋
docs : 문서 수정에 대한 커밋
style : 코드 스타일 혹은 포맷 등에 관한 커밋
refactor :  코드 리팩토링에 대한 커밋
test : 테스트 코드 수정에 대한 커밋
```

### ✏️PR 규칙

- 신규개발 - feature/#issue_number 생성 후 PR
- 라벨링
  - `In Progress` - 개발 진행중
  - `Asking for Review` - 코드리뷰 필요
  - `refactoring` - 리뷰 후 리팩토링 필요

- 리뷰어 중 1명 이상의 `Approve` 를 받아야 `Merge pull request` 가능
- `push` 을 할 때마다 gitaction build가 자동으로 실행되며 단위테스트, 통합테스트에 모두 통과되어야 `Merge pull request`가능
