##  GitHub Actions: Auto-Close Issues Test

이 레포지토리는 GitHub Actions를 사용해 PR이 **메인 브랜치가 아닌 브랜치로 병합**되더라도 연결된 이슈가 자동으로 닫히도록 하는 기능을 테스트하기 위해 만들어졌습니다.

### 목적
- `closes #이슈번호`와 같은 키워드로 연결된 이슈를 PR 병합 시 자동으로 닫기
- `main` 외에도 `dev`, `dev-fe`, `dev-be` 등 다양한 브랜치 병합을 감지하도록 설정

### 테스트 중인 기능
- PR 병합 시 linked issue 자동 종료
- 특정 브랜치에서만 워크플로우 실행 조건 지정

### 참고
- GitHub Actions Workflow: `.github/workflows/auto-close.yml`
