# MORI Stories — 브랜드 미디어 사이트 (프로토타입)

모든 HTML·이미지·영상·에셋을 이 폴더 하나에서 관리합니다. (파일 흩어짐 방지)

## 구조
```
MORI-Stories/
├─ index.html                         진입점 (허브로 리다이렉트)
├─ mori-stories-2026-07-01.html       허브 (목록/필터/이번 주/최신/구독)
├─ mori-insight-article-2026-06-30.html   인사이트/뉴스 fallback 상세
├─ mori-news-book-2026-07-02.html     뉴스 상세 (통상뉴스 책 소개)
├─ mori-seminar-academy-2026-07-02.html   세미나 상세 (오픈세미나+신청)
├─ mori-field-story-campus-tour-2026-07-02.html   현장 스토리 (캠퍼스 투어)
├─ mori-playbook-*.html (6)           세일즈 플레이북 아티클
└─ assets/                            이미지·영상·로고 전부
   ├─ mori-icon.gif                   로고
   ├─ mori-stories-hero.mp4 / mori-hero.mp4   히어로 영상
   ├─ mori-signal-reader.mp4          세미나 소개 영상
   ├─ mori-seminar-poster.png / -hero.jpg     세미나 포스터/히어로
   ├─ mori-book-cover.jpg             책 표지 (뉴스)
   └─ campus-1~4.(png/jpeg)           현장 스토리 사진
```

## 카테고리 (4)
홈 · 인사이트 · 뉴스 · 세미나 · 현장 스토리

## 규칙
- HTML은 폴더 루트, 미디어/에셋은 assets/ 에만.
- HTML 간 링크 = 파일명(루트), 에셋 참조 = `assets/파일명`.
- 새 페이지/이미지 추가 시에도 이 폴더 안에서만 관리.

> 설계서(SSOT): connect-ai-plan/mori/specs/94-stories-content-hub-cms-v1.0.md
