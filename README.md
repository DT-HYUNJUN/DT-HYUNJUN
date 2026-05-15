# 박현준 — Frontend Developer

협업과 소통을 핵심 가치로 삼는 프론트엔드 개발자입니다.  
크로스 보더 쇼핑 플랫폼 스타트업에서 관리자 사이트 프론트엔드를 단독으로 개발·유지보수했습니다.

📮 angle307@naver.com

---

## Skills

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React Query](https://img.shields.io/badge/React_Query-FF4154?style=flat-square&logo=reactquery&logoColor=white)
![Zustand](https://img.shields.io/badge/Zustand-443E38?style=flat-square)
![MUI](https://img.shields.io/badge/MUI-007FFF?style=flat-square&logo=mui&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)

Architecture: FSD · Git Flow

---

## Experience

**와이오엘오 (YOLO Corp.)** · Frontend Intern · 2024.07 – 2025.07

해외 직구 크로스 보더 쇼핑 플랫폼 *크로켓* 운영 스타트업.  
관리자 사이트 프론트엔드 단독 개발 (신규 70% · 유지보수 30%)

- 테마전 상품 등록 자동화 (엑셀 업로드 · 드래그 앤 드롭) — 작업 시간 **95% 감소** (8,000초 → 400초/월)
- React Query Optimistic Updates 적용 — 유저 리스트 응답 대기 **0초 수렴**
- 백엔드 팀 관리 하의 관리자 사이트를 인수받아 서비스 디자인 시스템 자발적 도입, UI 일관성 확보
- 결제 내역 페이지 레거시 마이그레이션 (쿠폰 할인·수수료 계산 로직 React로 정확히 재구현)
- 외부 AI 협업사 API 연동 — Before/After 체계적 정리로 신속한 대응 이끌어냄

---

## Problem Solving

**MUI 커스텀 한계 극복**  
`sx prop` · `styled API` · `theme override` 조합으로 디자인 명세 충족. 이 경험을 바탕으로 관리자 사이트 전체에 디자인 시스템 도입.

**레거시 API 타입 불일치**  
동일 엔드포인트에서 케이스별로 다른 응답 타입 발생 → 반복 테스트로 모든 케이스 수집 후 TypeScript 유니온 타입으로 안전하게 처리.

**React Query 단기 학습**  
공식 문서 기반으로 빠르게 학습하여 즉시 실무 적용. 이후 Optimistic Updates · 캐싱 전략까지 확장하여 UX 개선에 직접 기여.

---

## Projects

**CocktailAB** — 칵테일 정보 검색 웹 서비스 · [cocktailab.vercel.app](https://cocktailab.vercel.app)

`React` `TypeScript` `FSD` `Zustand` `React Query` `GitHub Actions` `Vercel`

- FSD 아키텍처 도입으로 기능 단위 응집 구조 전환, 도메인별 수정 영향 범위 최소화
- Redux Toolkit → Zustand + React Query 분리로 관심사 분리 및 보일러플레이트 감소
- Netlify 수동 배포 → GitHub Actions CI/CD 자동화
- 모바일 단일 레이아웃 → PC · 태블릿 · 모바일 반응형 전환
