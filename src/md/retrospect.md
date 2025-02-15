**회고는 노션으로 혼자 하고 있지만, 노션과 다른 방향으로 회고합니다.**

# 회고

## 1주차

> ### CLI와 Git
>
> Shell은 컴퓨터에게 명령할 수 있는 프로그램입니다. Shell 중 하나가 CLI입니다.  
> Shell은 CLI(command line interface), gui(graphic user interface), nui(natural user interface) 등이 있습니다.  
> 주요 사용하는 셀은 Bash, Zsh, Fish powershell 등이 있습니다.
>
> Git은 리누스 토발즈가 개발한 분산 버전 관리 시스템입니다.  
> 스냅샷 모델을 사용해서 저장소에서 관리하는 특정 시점의 모든 내용을 저장합니다.  
> Working Directory, Staging Area, Repository의 세 영역을 가집니다.

---

> ### CLI 명령어
>
> 1. `pwd`: 현재 경로를 출력
> 2. `mkdir` : 디렉토리를 만듦
> 3. `cd` : 디렉토리로 이동
> 4. `ls` : 디렉토리와 파일의 목록을 출력
> 5. `touch` : 빈 파일 생성
> 6. `echo` : 내용이 들어있는 파일 생성
> 7. `cat` : 파일의 내용을 출력
> 8. `rm` : 폴더를 제거
> 9. `rmdir` : 디렉토리를 제거
> 10. `mv` : 디렉토리나 파일을 이동 / 이름 변경
> 11. `cp` : 디렉토리나 파일을 복사
> 12. `clear` : CLI 창을 위로 올림..?
> 13. `whoami` : 유저를 출력
> 14. `&&` : 명령 두 개 사이에 사용해서 연달아 하는 명령 입력
> 15. `$_` : &&를 이용해서 두 개 이상의 명령을 연달아 할 때, 앞 인자를 가리킬 때 사용

---

> ### Git 명령어
>
> 1. `git init` : 저장소 생성
> 2. `git status` : 현재 상태 확인
> 3. `git add` : 파일의 변경 사항을 index(Staging Area)에 추가
> 4. `git restore` : 작업 내용 취소
> 5. `git commit` : 파일의 변경 사항에 대한 이력 생성
> 6. `git log` : 커밋 이력 확인
> 7. `git checkout HEAD~` : 과거 커밋 이력 확인
> 8. `git reset HEAD~` : 이전 상태로 복원(이력 제거)
> 9. `git branch` : 브랜치 생성 및 이동
> 10. `git reset HEAD~` : 이전 상태로 복원(이력 제거)
> 11. `git remote` : 리모트(Remote) 브랜치
> 12. `git push` : 로컬의변경 이력을 리모트로 전송
> 13. `git pull` : 리모트의 내용을 로컬에 반영 (fetch + merge)
> 14. `git merge` : 브랜치 병합하기

---

## 2주차

### Figma

> 웹 기반의 UI 설계 툴입니다.  
> 컴포넌트를 사용한 설계가 피그마의 핵심입니다.  
> 피그마에서 가장 중요한 것이 다섯 가지 있습니다.
>
> 1. Component & Instance
> 2. Component Varitants
> 3. Component Properties
> 4. Autolayout
> 5. Local variable

### HTML

> HyperText Markup Language의 줄임말로, 마크업 언어 입니다.  
> html 요소 안에 head 요소와 body 요소가 순서대로 자식 요소로 위치해 있습니다.

#### Head 요소

> head 요소는 문서 메타정보와 관련된 정보들을 포함하는 요소로 이루어져 있습니다.  
> title, base, link, meta, style 등의 요소가 속합니다.

#### Body 요소

> ##### 제목과 단락
>
> h1, h2, h3, h4, h5, h6 요소를 사용하여 제목을 나타냅니다.  
> 뒤 숫자가 작을 수록 높은 등급의 제목입니다.  
> p 요소를 사용하여 단락을 나타냅니다.  
> 용도, 강조, 사용 방향에 따라 pre, blockquote, address, cite, b, em, strong, em, i, small, sub, sup, ins, del, mark 등의 요소를 사용합니다.
>
> ##### 이미지와 피규어
>
> img 요소를 사용하여 이미지를 나타냅니다.  
> src 속성과 alt 속성을 함께 사용해야 합니다.  
> src 속성에는 이미지의 경로를, alt 속성에는 이미지를 대체할 텍스트를 값으로 줍니다.  
> figure 요소로 img 요소를 감싸서 figure 구역을 설정해 둘 수 있습니다.  
> figure 요소에 figcaption 요소를 자식요소로 줄 수 있습니다.  
> figcaption 요소로 img 요소의 제목, 내용 등을 적어 표현할 수 있습니다.
>
> ##### 앵커
>
> a 요소를 사용하여 하이퍼링크를 나타냅니다.  
> href 속성과 함께 사용해야 합니다.  
> href 속성에 하이퍼링크의 경로를 값으로 줍니다.  
> 글로벌 속성인 title 속성을 사용하여 툴팁을 표현하는 것이 좋습니다.  
> target 속성으로 새 탭, 새 창에서 링크를 연결할 수 있습니다.  
> 새 탭, 새 창에서 열 때는 rel 속성에 noopenner, noreferer 속성을 사용해야 합니다.
