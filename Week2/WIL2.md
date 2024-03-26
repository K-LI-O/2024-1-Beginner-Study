#WIL2

0 공지 및 안내 – 제출 명세 지켜달라.

1 복습 : stages, git/github의 흐름(working staging local repo remote repo). Git 명령어 재언급 - Git init, git add ~, git commit - ~, git push origin main 등. 커밋 메시지 명확성 언급 및 $ 사인 및 꺽쇠 적지말라.

2 Fork & star : Fork - 다른 사용자의 리포지토리를 자신의 계정으로 복사하여 독립적으로 수정하고 관리한다. 다수가 사용하는 오픈소스 서비스가 있을 때, fork를 이용하여 개선을 제안할 수 있다. 핵심 내용은 아니지만 이런 기능도 있다 정도로. Star – 관심 있는 리포지토리나 프로젝트를 북마크하는 기능.

3 Issue : 리포지토리에서 작업 계획, 토론 및 추적을 위해 활용. 예시 – 오타 발견이나 로직 변화, 정책 변화 등의 사건 발생 시, 이용 가능.

4 Branch : 기존 브랜치에서 분기하여 생성하는 별도의 작업 공간. Fork와 달리 같은 리포지토리에 생성. Convention – “type/issue번호 - 설명” 권장.

5 Pull Request : 분기한 브랜치를 다시 메인 브랜치로 병합함. 새로운 변경을 제안하거나 병합 시 발생하는 충돌을 해결. Merge에 앞서 코드를 리뷰한다.

6 merge : 3가지 옵션. Create merge commit/squash and merge/rebase and merge. Merge 과정에서 충돌 다수 발생, 뭔가 모르겠으면 그냥 create 권장. Merge commit – 두 브랜치를 공통 부모로 하는 새로운 커밋 생성, 브랜치의 커밋들이 그대로 메인 브랜치로 병합. Squash – 브랜치의 커밋을 통합하여 하나의 커밋으로 병합한다. Rebase – 커밋의 시작점 변경, 모두 새로운 커밋으로. Rebase 시 Commit hash 변경 – 충돌 가능성 있으니 지금은 사용을 자제하시라. Commit hash – 진짜 이름은 commit id. 커밋 식별자, 40자 길이 16진수.

7 실습 : 브랜치 생성, 브랜치 삭제, 브랜치 이동하여 파일 생성. 이후 Pull request. Pull request 할 때 Reviewer, label 처리 언급.

8 요약 : Fork, star는 잊어버려도 나머지 네 가지는 기억할 것. Merge의 3가지 옵션. 과제할 때는 squash 이용. 브랜치 이름의 컨벤션 지키기를 당부.

+ https://github.com/K-LI-O/2024-1-Beginner-Study/pull/2/
