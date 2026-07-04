# 조대형의 주식 노트

주식·투자·시장 분석 기록. [Astro](https://astro.build) 정적 블로그 → GitHub Pages 자동 배포.

- **사이트**: https://daehyoung.github.io/stock/
- **글 위치**: `content/posts/*.md` (frontmatter: `title`, `date`, `tags` …)
- **배포**: `main`에 push → GitHub Actions(`.github/workflows/deploy.yml`)가 빌드·배포. 매일 09:00 KST cron 리빌드로 미래 날짜 글 자동 공개(예약 발행).

## 로컬 개발

```bash
npm install
npm run dev      # 개발 서버
npm run build    # 정적 빌드 (dist/)
```

## 라이선스

- 글·콘텐츠: [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/)
- 코드·설정: 저장소 `LICENSE` 참조
