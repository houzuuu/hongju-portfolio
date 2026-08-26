# HONGJU Portfolio

개인 포트폴리오 웹사이트 작업 폴더입니다.

## 현재 구성

- `index.html`: 화면 스타일, 프로젝트 데이터, 인터랙션, Three.js 3D 로고가 모두 포함된 단일 HTML 파일
- `images/`: 프로젝트 이미지와 파비콘을 둘 폴더
- `videos/`: 프로젝트 영상을 둘 폴더

## 현재 확인된 상태

- HTML 문서는 한국어 페이지, 반응형 레이아웃, 작품/소개 탭, 프로젝트 상세 화면으로 구성되어 있습니다.
- 외부 연결: Google Fonts, Pretendard CDN, Three.js CDN
- HTML에서 참조하는 로컬 미디어는 총 106개입니다.
- GitHub `houzuuu/hongju-portfolio`의 `main` 브랜치를 최신 기준으로 삼아 `images`와 `videos`를 동기화했습니다.
- HTML이 참조하는 106개 미디어가 모두 존재합니다.
- 동기화 전 로컬 미디어는 `_backup/pre-github-sync-20260826`에 보관했습니다.

## 필요한 폴더 구조

```text
포폴 홈페이지/
├── index.html
├── images/
│   ├── favicon.png
│   └── 프로젝트 이미지들
└── videos/
    └── starfield-2025-winter-isp-motion.mp4
```

## 다음 정리 권장 순서

1. `ASSET-REPORT.md`의 누락 파일을 추가로 찾습니다.
2. 임시 대응된 이미지가 프로젝트 내용과 정확히 일치하는지 화면에서 확인합니다.
3. 데스크톱·모바일 레이아웃과 프로젝트 이동을 확인합니다.
4. 기능 확인 후 단일 HTML의 CSS와 JavaScript를 별도 파일로 분리합니다.

외장하드 원본은 수정하지 않았으며 홈페이지 폴더에는 복사본만 만들었습니다.
