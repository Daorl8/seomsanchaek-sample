# STRUCTURE · seomsanchaek-sample (v0.1 · 계절 달력)

```
seomsanchaek-sample/
├─ index.html                 단일 파일 (CSS·JS 인라인)
├─ wrangler.toml              name = seomsanchaek-sample → seomsanchaek-sample.lgt3232.workers.dev (Worker 이름도 같게)
├─ .assetsignore              img/ · _old/ · 문서 · index_*.html · _deploy 배포 제외
├─ sm-gowun.woff2             제목 (고운돋움, 쓰는 글자만)
├─ sm-pretendard.woff2        본문 (Pretendard 400–700, 쓰는 글자만)
├─ sm-logo.webp               세로 손글씨 로고 (먹색)
├─ sm-hero.webp               히어로 레몬 빙수
├─ sm-plum / syrup            봄
├─ sm-summer / blueberry      여름
├─ sm-figfarm / fig           가을
├─ sm-sea                     겨울방학
├─ sm-bingsu / chestnut / cake / watermelon / latte / tea   한 그릇, 한 잔
├─ sm-window / door / flowers / entry                       공간
├─ sm-sign                    오시는 길 간판
├─ favicon.png · og-seomsanchaek.jpg
├─ img/                       다올 제공 원본 56장 (배포 제외)
└─ CHANGELOG.md / STRUCTURE.md
```

## 섹션 순서
안내 띠(민트) → 헤더 → 히어로 → `#seasons`(띠색 · 겨울은 민트 면) → `#menu` → `#space`(띠색) → `#visit` → 푸터 + 모바일 `.quick`.

## 겨울방학 문구 위치 (방학 끝나면 3곳 수정)
상단 `.notice` 띠 · `#seasons .winter` · `#visit` 영업 칸 small.

## 색 규칙
원목 #8A5A36 = 라벨 · 채움 버튼. 민트 #BFE3DA = 안내 띠 · 겨울 칸만.

## 그리드
모든 그리드 칸 `minmax(0, …)`(LESSONS §27).

## 폰트 재생성
문구 바꾸면 빠진 글자 검사(LESSONS §26). 두 서브셋 모두 다시.
