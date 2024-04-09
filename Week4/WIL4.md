#WIL4

0 공지 : 수료 기준, 우수 스터디원 선정.

1 복습 : HEAD – 현재 작업 중인 위치. 현재 작업 중인 브랜치의 가장 최근 커밋. 커밋을 되돌리는 방법 – amend – 기존의 커밋을 수정할 때 사용(커밋 메시지, 코드 등), 커밋 아이디 변화하므로 사용할 때 주의해야, reset – 커밋 제거, soft, mixed, hard 3가지 옵션 존재, revert – 커밋을 되돌리고, 되돌림에 대한 commit 생성.

2 개요 : 브랜치 전략 – git flow, github flow. 개발자로서의 태도.

3 브랜치 관리의 필요성 : 작업 영향 줄이려 브랜치 관리 필요, 배포와 관련하여 관리의 필요성 존재. 브랜치 보호 규칙 – 모르고 프젝하는 것보다 일단 있다는 것은 알아두기를, 승인을 통해 pull request 병합, 브랜치의 push 가능자 지정 등.

4 브랜치 전략 : 여러 가지 있지만 대중적인 것 가져옴. Git flow – 브랜치를 관리하기 위한 전략.

5 브랜치 종류 – main – main(master), develop supporting – feature, release, hotfix. 메인 브랜치는 삭제하지 않음. Main – 프로젝트 생성 시의 기본 브랜치, 영구히 존재. 병합될 때마다 새로운 버전. Main 또는 master를 사용. Develop – 영구히 존재하는 두번째 브랜치, Feature의 기반. Feature - develop에서 분기하여 작업, 기능 개발 완료 후 develop으로 병합. 이름은 자유 지정이나 기존의 브랜치 이름은 제외. Release – 배포 준비 브랜치, 자잘한 버그를 수정 및 QA 작업, develop에서 분기하여 main 병합. Hotfix – 배포 환경에서 즉각적인 수정이 필요한 경우 사용, main에서 분기, main, develop 모두에 병합 필요. 속도감 필요한 작업일 경우 사용.

6 git flow의 사용 관련 : git flow 제안자가 현재 앱 개발 과정과 격세지감…어쩌구로 github flow 사용 제안 – 배포 수시로 하는 상황에 git flow는 부적절 – release 브랜치와 브랜치 보호 규칙 등으로 시간 지연이 크다.

7 github flow : 브랜치 종류 – main, feature. Main – git branch와 다르지 않음, 항상 배포 가능 상태로 유지, 병합 전에 충분한 test 후 merge. Feature – 다른 브랜치들을 구분하지 않음, main에서 분기하여 작업 후 다시 main 병합, 브랜치의 목적을 이름에 잘 담아야, git flow에 비해 코드 리뷰가 더 중요해짐(충분한 test와 같은 맥락).

8 뭘 써야? – 상황에 따라 적절하게 사용.

9 개발자적 태도 – convention, 구글링, 코드에 대한 주인 의식(좋은 설계) – 윤 교수님 왈 '너는 코더가 아니라 아키텍처다'…, 질문을 잘 하자(좋은 질문).
