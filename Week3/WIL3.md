#wIL3

0 공지 – 1, 2주차 복습 당부. 3주차부터는 실습 대신 퀴즈.

1 복습 – issue 생성. Branch 이용하여 작업 – 다중 작업 시 엉키는 상황 방지. 브랜치 명령어 - 브랜치 확인, 브랜치 생성 및 삭제, 브랜치 이동, 생성 및 이동. Pull request – 분기한 branch 병합하기 위한 절차, 병합 시의 충돌 해결. Merge – 3가지 옵션, create or squash 많이 사용할 것. 다른 하나는 rebase. 

2 사전 지식 – git log – commit 기록을 최신순으로 확인. –-oneline 옵션을 사용하면 각 커밋을 한 줄에 요약. 이를 사용하면 간결하게 볼 수 있다. 과제에도 Git log one line 옵션 사햑용할 듯해 보고 감. commit id – commit 식별자. 다양한 정보가 들어가 만들어지므로 중복 확률이 낮다. 뒤에서 자주 사용할 것 같아 짚고 넘어감. HEAD – 현재 작업 중인 위치를 가리킨다. 한 브랜치에서도 커밋은 여럿, 특정 커밋으로 이동하는 경우 최신 커밋 식별을 위해 head 이용. 새로운 커밋 추가한다면 head 갱신될 것. git status – 파일 생명 주기를 따라 파일 분류 및 확인.

3 커밋 삭제1 : amend – 마지막 commit을 수정할 때 사용. 커밋 아이디의 결정 요소 중 시간이 있었다 – 완전히 새로운 커밋으로 대체되므로 커밋 아이디 변화. Vim 진입하여 커밋 메시지 수정 – 진입 없는 커밋 메시지 수정 옵션 있음. 주의사항 – 커밋 아이디가 바뀌므로 누군가가 작업하는 commit은 amend 하지말 것. 사실 이들 중 뭔갈 하는 상황이라면 이미 큰일이 난 것.

4 커밋 삭제2 : Reset – 원하는 만큼 commit을 삭제. 3가지 옵션 존재 – soft, mixed(default), hard. Git reset ‘option’ 위험한 명령어이므로 커밋 아이디 여러 번 확인할 것. Soft – 커밋만 취소, 변경 사항이 한 단계 내려와 staging area에 저장. Mixed – 커밋 취소, 두 단계 내려와 working directory에 저장. 수정하려면 add부터 다시. Hard – 커밋 완전히 취소, 변경 사항을 모두 제거하고 이전 커밋으로 되돌아 감.

4 situation – 예시 상황 설명. Soft – 4, 5번째 커밋이 staging area 위치. Mixed – working directory 위치. Hard - 그냥 삭제. 여기까지가 reset 설명. 

5 커밋 삭제3 : revert – reset과 뭐가 다른지? Commit 기록 삭제 vs 커밋을 되돌리고 이에 대한 커밋 생성. Revert –no-edit – vim 진입 없이 바로 revert. 약간 더 수정하여 커밋하고 싶을 때 revert -–no-commit 옵션.

6 reset vs revert : reset은 커밋 삭제하므로 공동 작업 시 위험할 수도. Revert 주로 사용.

7 과제 : WIL3, 나머지 하나는 과제 명세 참조.
8 기타 : 디스코드 디엠으로 질문 받지 않겠다. 

