# AI 기술 주기율표

현대 AI 기술 스택을 주기율표 형식으로 시각화한 인터랙티브 대시보드

## 🌐 라이브 데모

배포 후 접속: https://statkclee.github.io/ai-periodic-table/

## 📊 주요 기능

- **24개 AI 원소**: 20개 주기율표 원소 + 4개 인프라 원소
- **16개 동위원소 데이터** (80% 커버리지): 실제 제품/서비스 구현체
- **8개 AI 아키텍처 패턴**: RAG, 자율 에이전트, 멀티 에이전트 등
- **완전 인터랙티브**: 클릭, 필터링, 동적 업데이트
- **Tufte 스타일 디자인**: 전문적이고 미니멀한 UI
- **2026년 최신 정보**: GPT-5.2, Claude 4.5, Gemini 3 등

## 🎯 3개 탭 구성

1. **주기율표**: 20개 원소 + 동위원소 탐색
2. **화학식**: 8개 AI 아키텍처 패턴
3. **사용법**: 완전한 가이드 및 설명

## 🛠️ 기술 스택

- Quarto Dashboard
- Observable JS (OJS)
- D3.js
- HTML/CSS

## 📦 로컬 실행

```bash
# 1. 저장소 클론
git clone https://github.com/statkclee/ai-periodic-table.git
cd ai-periodic-table

# 2. Quarto 설치 (https://quarto.org/docs/get-started/)

# 3. 대시보드 렌더링
quarto render

# 4. 로컬 미리보기
quarto preview
```

## 🚀 GitHub Pages 배포 설정

리포지토리가 생성되었습니다. 이제 GitHub Pages를 활성화하세요:

1. https://github.com/statkclee/ai-periodic-table/settings/pages 접속
2. **Source**: Deploy from a branch
3. **Branch**: `main` 선택
4. **Folder**: `/docs` 선택
5. **Save** 클릭

약 1-2분 후 https://statkclee.github.io/ai-periodic-table/ 에서 접속 가능합니다.

## 📁 프로젝트 구조

```
ai-periodic-table/
├── index.qmd           # 메인 대시보드 소스
├── _quarto.yml         # Quarto 설정
├── styles.css          # 스타일시트
├── docs/               # 빌드 출력 (GitHub Pages)
│   ├── index.html
│   ├── .nojekyll
│   └── site_libs/
└── README.md
```

## 📈 데이터 커버리지

- **원소**: 24개 (주기율표 20 + 인프라 4)
- **동위원소**: 16개 원소에 구현체 정보 (80%)
- **화학식**: 8개 아키텍처 패턴
- **2026년 기준 최신 정보**

## 🎨 디자인 철학

Edward Tufte의 데이터 시각화 원칙을 따름:
- 미니멀 타이포그래피
- 데이터 중심 디자인
- 여백 활용
- 색상 코딩으로 정보 전달

## 📝 라이선스

MIT License

## 🙏 감사

2026년 최신 AI 기술 정보는 다음 출처를 참고했습니다:
- OpenAI, Anthropic, Google, Meta 공식 문서
- MTEB 벤치마크
- 다양한 오픈소스 프로젝트

---

Built with ❤️ using Quarto & Observable
