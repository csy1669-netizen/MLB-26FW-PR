# MLB 26FW 사내PR 대시보드

GitHub Pages 업로드용 정리본입니다.

## 구조
- `index.html`
- `assets/` : 경량화된 이미지/영상 (29개)

## 업로드 방법
저장소 루트에 `index.html`과 `assets` 폴더를 그대로 올리면 됩니다.
모든 경로가 상대경로(`assets/...`)라 별도 수정은 필요 없습니다.
이후 Settings > Pages 에서 브랜치를 지정하면 배포됩니다.

## 변경 이력 (v8)
- 히어로 이미지: CMYK 원본(20MB) -> sRGB 변환본으로 교체, 로컬 절대경로를 상대경로로 수정
- 히어로 이미지에 width/height 지정 (로딩 중 레이아웃 시프트 방지)
- `.nb{white-space:nowrap}` 유틸 추가 — 지정 구간 줄바꿈 방지
- 폰트 폴백에 Noto Sans KR 추가 (CDN 차단 환경 대응)
- 미사용 에셋 `명동PSD T18_하단.jpg`(20MB) 제외

## 용량
- 전체 약 9.3 MB
