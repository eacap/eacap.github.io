# EAGCAP 홈페이지 시작 안내

## 어떤 파일이 무슨 일을 할까?

- `assets/css/style.css`: **디자인**. 가장 위의 `:root`에서 색상, 글꼴, 배경 등을 바꿀 수 있어요.
- `index.html`: 메인 화면 **배치/레이아웃**.
- `_layouts/default.html`: 모든 페이지의 **공통 메뉴와 하단 영역**.
- `_data/home.yml`: 학회 이름, 연도, 날짜, 한 줄 소개, 제출 폼 주소 등 **매년 바뀌는 정보**.
- `about/index.md`, `cfp/index.md`, `program/index.md` 등: 각 페이지의 **본문**.
- `_posts/`: 새 공지 글이 저장되는 곳. CMS에서 입력하면 자동으로 파일이 만들어집니다.
- `.pages.yml`: 후배들이 Pages CMS에서 어떤 내용을 편집할 수 있는지 정하는 **관리 화면 설정**.

## 1. GitHub에 업로드하기

아래 순서를 따르세요. **압축파일(.zip) 자체를 GitHub에 업로드하면 홈페이지가 되지 않습니다.** 압축을 풀어서 안쪽 파일과 폴더를 올려야 합니다.

**간편한 방법: GitHub Desktop 프로그램**

1. GitHub Desktop을 설치하고 GitHub 계정으로 로그인합니다.
2. `File → Clone repository`에서 `eagcap/eagcap.github.io`를 선택합니다.
3. 컴퓨터의 복제된 `eagcap.github.io` 폴더에 이 압축파일을 푼 **안쪽 파일들을 전부 복사**합니다. (`.pages.yml`처럼 이름이 점으로 시작하는 숨김 파일도 포함하세요.)
4. GitHub Desktop에 변경 파일 목록이 나타나면 아래 Commit 메시지에 `Initial conference site`를 입력한 후 `Commit to main`을 누릅니다.
5. 위쪽 `Push origin`을 눌러 온라인 GitHub에 업로드합니다.
6. GitHub 저장소의 `Settings → Pages`에서 `Deploy from a branch`를 선택하고 `main` / `/(root)`로 설정한 다음 Save를 누릅니다.
7. 배포가 끝나면 `https://eagcap.github.io/`에서 열어봅니다.

만약 기본 브랜치 이름이 `main`이 아니면 실제 브랜치 이름을 사용합니다. GitHub Desktop이 변경 파일을 감지하지 않으면 복사한 위치가 올바른지 확인하세요.

## 2. Pages CMS 연결하기

1. `https://app.pagescms.org/` 접속 → GitHub 계정으로 로그인.
2. Pages CMS GitHub App을 **eagcap 조직**에 설치하고 접근 저장소를 `eagcap.github.io`로 제한합니다.
3. 편집 목록에 Announcements, Home page settings, About, CFP, Program 등이 나타나는지 확인합니다.
4. Announcements에서 시험 공지를 만들고 게시해 봅니다. 저장하면 GitHub에 반영되고, GitHub Pages의 재빌드 후 화면에 표시됩니다.
5. 후임 편집자는 Pages CMS에서 이메일로 초대할 수 있습니다. 일반 공지 편집에는 GitHub 코딩 지식이 필요하지 않습니다.

## 3. 네가 디자인하는 방법

- 마음대로 디자인해도 됩니다. **템플릿을 새로 고를 필요는 없습니다.** 지금 제공된 디자인은 시작용 기본형입니다.
- VS Code에서 `style.css`와 HTML 레이아웃 파일을 고치면 색상, 여백, 글꼴, 카드/메뉴 배치를 수정할 수 있습니다.
- Canva에서 먼저 화면 구성을 그린 다음 CSS/HTML로 구현해도 좋습니다. 다만 **Canva를 수정했다고 GitHub 홈페이지가 자동으로 바뀌는 것은 아닙니다.**
- Pages CMS는 **글과 데이터 편집용**이지, Canva처럼 화면에서 디자인 요소를 드래그하는 도구는 아닙니다.
- Jekyll 문법 `{{ ... }}`와 `{% ... %}`는 데이터를 표시하는 부분이므로, 처음에는 그대로 두고 주변 HTML/CSS만 변경하는 것을 권장합니다.

## 4. 제출 기능: 아직 연결 전

- `Home page settings → submission_url`이 현재 비어 있으므로 **실제 PDF 제출은 아직 받지 않습니다**.
- 추후 보안과 개인정보 처리가 가능한 **별도 제출 서비스**를 정하고 테스트한 후 URL을 입력하면 메인 화면에 제출 버튼이 나타납니다.
- 지원자의 개인정보나 심사용 비공개 논문을 **공개 GitHub 저장소에 보관하면 안 됩니다**.
- 중국 본토에서 사이트와 별도 제출 폼이 *모두* 정상적으로 작동하는지 확인하는 것이 중요합니다.

## 5. 매년 인수인계하기

- Pages CMS의 Home page settings에서 연도·날짜·장소 수정.
- Conference editions에 해당 연도를 추가하고 기존 연도는 유지.
- Announcements에서 새 공지 추가. 기존 공지는 그대로 보관.
- 새 운영진을 편집자로 초대하고 GitHub 조직의 Owner 권한을 최소 두 명 이상에게 유지.

**공개 전에 확인할 것:** `East Asian Graduate Conference in Philosophy`는 작업용 학회 명칭입니다. 공식 명칭, 소개, CFP, 담당 이메일을 확정한 뒤 변경하세요.
