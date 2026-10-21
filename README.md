# AURA LAB — GitHub Pages

한소율 연구실 AURA LAB 홈페이지

## GitHub Pages에 게시하기

1. GitHub 저장소를 만들고 이 폴더의 파일을 저장소 최상위에 올립니다. 사이트 첫 화면 파일인 `index.html`은 최상위에 있어야 합니다.
2. 저장소의 **Settings → Pages**에서 **Deploy from a branch**를 선택합니다.
3. 배포 브랜치(보통 `main`)와 폴더 `/(root)`를 선택하고 저장합니다.
4. 개인 사이트 주소를 쓰려면 저장소 이름을 `사용자명.github.io`로 정합니다. 다른 저장소 이름도 Pages 설정으로 게시할 수 있습니다.


## 학생 증명사진 넣기

사진 파일을 `images/students/`에 넣고 아래 이름으로 저장하면 Students 탭에서 자동으로 표시됩니다. 권장 비율은 세로 3:4이며 JPG, PNG, WebP를 사용할 수 있습니다. 다른 확장자를 쓰면 `index.html`의 `members` 데이터에서 해당 `photo` 경로를 바꾸세요.

| 학생 | 파일명 |
|---|---|
| 김에스더 | `esther-kim.jpg` |
| 김부빈 | `bubin-kim.jpg` |
| 김태연 | `taeyeon-kim.jpg` |
| 원태연 | `taeyeon-won.jpg` |
| 홍성민 | `seongmin-hong.jpg` |

실제 사진 파일이 아직 없으면 카드 안에 이니셜 자리표시자가 표시됩니다. 학생 카드는 넓은 화면에서 2열, 좁은 모바일 화면에서 1열로 배치됩니다.

## 내용 수정

논문, 강의, 구성원, 소식, 사진 등의 내용은 `index.html`의 `site-data` JSON 블록에서 바꿀 수 있습니다. HTML 편집기로 파일을 열고 해당 목록의 항목을 수정한 뒤 저장소에 다시 올리면 됩니다. 
