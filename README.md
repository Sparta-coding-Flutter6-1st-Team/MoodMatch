# MoodMatch

### 깃 컨벤션
#### 커밋 메시지 예시:
csharp
Dev-71 Feat: add new feature

#### 태그 종류:
```
Feat: 새로운 기능을 추가할 경우
Fix: 버그를 고친 경우
Design: CSS 등 사용자 UI 디자인 변경
Style: 코드 포맷 변경, 세미 콜론 누락, 코드 수정이 없는 경우
Refactor: 프로덕션 코드 리팩토링
Comment: 필요한 주석 추가 및 변경
Docs: 문서를 수정한 경우
Test: 테스트 추가, 테스트 리팩토링(프로덕션 코드 변경 X)
Rename: 파일 혹은 폴더명을 수정하거나 옮기는 작업만인 경우
Remove: 파일을 삭제하는 작업만 수행한 경우
```
#### 브랜치 네이밍 규칙:
```
main: 안정적인 코드
dev: 개발 중인 코드
dev-이슈번호: 특정 이슈에 대한 개발 브랜치 (예: dev-xx)
```
#### PR 템플릿 예시

PR을 생성할 때는 다음과 같은 템플릿을 사용하여 변경 사항을 설명할 수 있다.

```
## PR Description 
### Summary description height error 
### Details 전체화면 진입 시 main detail 페이지의 description 스크롤 문제를 해결했습니다. 

### Type(s) of Changes - 
🐛 Bug fix - 
✨ New feature - 
🛠️ Enhancement (optimization, refactoring, etc.) - 
📖 Documentation - 
🛰️ Other (please specify): 

### Related Issues Jira Ticket or Issue Link Link to the relevant Jira ticket or issue. 
### Checklist 
#### Code Review Checklist 
- [ ] Changes have been tested locally 
- [ ] Make sure you followed the code convention 
- [ ] No console warnings or errors 
- [ ] Components are properly documented (PropTypes or TypeScript interfaces) 
- [ ] State and props have been properly managed 
- [ ] Unused code and dependencies have been removed 
- [ ] Documentation has been updated (if applicable) 
- [ ] UI changes have been reviewed and approved 

### 버전 - "your project version"
### 설치 방법 
