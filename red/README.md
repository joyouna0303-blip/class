# Dear Diary — 순수 HTML/CSS 메인 화면

기존 React 프로젝트와 분리된 정적 웹페이지입니다. 프레임워크, 패키지 설치, JavaScript가 필요하지 않습니다.

## 파일 구조

```text
red/
├── index.html
├── README.md
└── css/
    └── style.css
```

## 로컬에서 확인하기

1. 저장소에서 `red` 폴더를 내려받거나 저장소를 복제합니다.
2. `red/index.html` 파일을 브라우저에서 엽니다.
3. HTML은 `index.html`, 색상·간격·반응형 디자인은 `css/style.css`에서 편집합니다.

## GitHub Pages로 게시하기

이 웹사이트가 `red` 폴더 안에 있으므로, GitHub Pages에서 이 폴더를 직접 게시 폴더로 선택할 수 있는 설정은 제한적입니다. 가장 간단한 방법은 별도 브랜치 또는 저장소의 최상위에 이 폴더의 파일들을 두는 것입니다. 현재 저장소 설정에 맞춰 Pages를 설정하기 전에는 실제 공개 주소가 생성되었다고 볼 수 없습니다.

## 폴더 링크 안내

메인 화면의 Daisy, Momo, Lulu, June 폴더는 각각 `pages/daisy.html`, `pages/momo.html`, `pages/lulu.html`, `pages/june.html`로 연결됩니다. 개인 페이지 파일은 아직 포함하지 않았으므로 해당 페이지를 만들기 전까지 링크는 작동하지 않습니다.

## 디자인 수정 포인트

`css/style.css` 상단 `:root`에서 주요 색상을 변경할 수 있습니다.
- `--pink`: Daisy
- `--yellow`: Momo
- `--lavender`: Lulu
- `--blue`: June
- `--page`: 바깥 배경색
- `--ink`: 기본 글자색

HTML의 `<link rel="stylesheet" href="css/style.css">`가 CSS 파일을 불러옵니다. 웹페이지 본문에서 CSS 파일 자체를 여는 일반 링크가 필요한 경우 `<a href="css/style.css">CSS 파일 보기</a>` 형태를 사용할 수 있습니다.