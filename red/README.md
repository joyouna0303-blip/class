# Dear Diary — 순수 HTML/CSS 메인 화면

기존 React 프로젝트와 분리된 정적 웹페이지입니다. 프레임워크, 패키지 설치, JavaScript가 필요하지 않습니다.

## 파일 구조

```text
red/
├── index.html
├── README.md
├── css/
│   └── style.css
└── pages/
    ├── daisy.html
    ├── momo.html
    ├── lulu.html
    └── june.html
```

## 로컬에서 확인하기

1. 저장소를 내려받거나 복제합니다.
2. `red/index.html` 파일을 브라우저에서 엽니다.
3. HTML 구조와 폴더 링크는 `index.html`, 색상·간격·반응형 디자인은 `css/style.css`에서 편집합니다.

## 폴더 링크 안내

메인 화면의 네 폴더는 HTML의 `<a>` 요소로 개인 페이지에 연결되어 있습니다.

- Daisy → `pages/daisy.html`
- Momo → `pages/momo.html`
- Lulu → `pages/lulu.html`
- June → `pages/june.html`

각 개인 페이지에는 메인 화면으로 돌아가는 링크도 있습니다. 현재 페이지들은 기본 템플릿이므로 사진, 글, 개인별 콘텐츠를 추가해 꾸밀 수 있습니다.

## GitHub Pages로 게시하기

1. 저장소의 **Settings → Pages**로 이동합니다.
2. **Build and deployment**에서 **Deploy from a branch**를 선택합니다.
3. 브랜치 `main`, 폴더 `/ (root)`를 선택하면 저장소 루트가 게시됩니다.
4. 이 프로젝트는 `red/` 폴더 안에 있으므로, `red/index.html`을 바로 사이트 첫 화면으로 게시하려면 `red` 폴더를 별도 저장소의 루트로 옮기거나, Pages 설정에 맞게 파일 구조를 조정해야 합니다.

## 디자인 수정 포인트

`css/style.css` 상단 `:root`에서 주요 색상을 변경할 수 있습니다.

- `--pink`: Daisy
- `--yellow`: Momo
- `--lavender`: Lulu
- `--blue`: June
- `--page`: 바깥 배경색
- `--ink`: 기본 글자색

이 프로젝트는 기존 React 프로젝트와 별개입니다. 기존 파일을 섞거나 덮어쓰지 않도록 `red/` 폴더 안에서 작업하세요.
