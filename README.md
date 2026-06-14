<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=200&section=header&text=shoman2&fontSize=60&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=AI%20Agent%20Engineer%20%7C%20LLM%20Harness%20Architect&descSize=20&descAlignY=58&descColor=a78bfa" />

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=3000&pause=800&color=A78BFA&center=true&vCenter=true&multiline=true&repeat=true&width=680&height=90&lines=Building+Multi-Agent+AI+Systems+%F0%9F%A4%96;LLM+Harness+%26+Orchestration+Engineering;Automating+Complex+Workflows+at+Scale" alt="Typing SVG" />

<br/>

[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:kimtaeyou0923@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/shoman2)

</div>

---

## 🧠 About Me

```python
class AIEngineer:
    name       = "TAE YOU KIM (shoman2)"
    focus      = ["AI Agent Systems", "LLM Harness Engineering", "Workflow Automation"]
    stack      = ["Python", "Claude SDK", "JavaScript", "pandas", "sklearn"]
    current    = "Building production-grade multi-agent exam authoring harness"
    philosophy = "Ship automated pipelines that replace 100x manual effort"
```

**AI Agent Harness** 전문 엔지니어. 복잡한 업무 흐름을 **오케스트레이터 → 전문 에이전트 → 검증 루프** 구조로 자동화합니다.  
행정안전부·해양수산인재개발원 등 공공기관 대상 LLM 기반 자동화 시스템 설계/구축/컨설팅 경험 보유.

---

## ⚙️ Tech Stack

### 🤖 AI / LLM
![Claude](https://img.shields.io/badge/Anthropic_Claude-D97706?style=flat-square&logo=anthropic&logoColor=white)
![Claude Code SDK](https://img.shields.io/badge/Claude_Code_SDK-7C3AED?style=flat-square&logo=anthropic&logoColor=white)
![Multi-Agent](https://img.shields.io/badge/Multi--Agent_Orchestration-0EA5E9?style=flat-square&logo=openai&logoColor=white)
![LLM Ops](https://img.shields.io/badge/LLM_Ops-10B981?style=flat-square&logo=openai&logoColor=white)

### 🐍 Python
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)

### 🌐 Frontend / Build
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![Netlify](https://img.shields.io/badge/Netlify-00C7B7?style=flat-square&logo=netlify&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)

### 🛠 Tools & Infra
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Chrome Headless](https://img.shields.io/badge/Chrome_Headless-4285F4?style=flat-square&logo=googlechrome&logoColor=white)
![Markdown](https://img.shields.io/badge/Markdown-000000?style=flat-square&logo=markdown&logoColor=white)
![JSON](https://img.shields.io/badge/JSON-000000?style=flat-square&logo=json&logoColor=white)

---

## 🚀 Flagship Project — AI Exam Authoring Harness

> **공공기관 AI 챔피언 시험 30세트 자동 출제 하네스** — 기관 첨부 자료만 넣으면 90개 문제지·해설·채점 솔버·PDF·CBT JSON까지 완전 자동 생성

```
[Input] 기관 제공 첨부 자료 (보도자료 · 법령 · 통계 · CSV)
   │
   ▼
[Round 0] attachment-analyzer  →  자료 분류 & 콘텐츠 유형 식별
[Round 1] set-designer         →  30세트 × 3과목 주제 매핑
[Round 2] question-writer ×90  →  문항 5개 + 시나리오 (병렬)
[Round 3] solve-writer   ×90  →  solve.py + 답안지 + 해설
[Round 4] leak-detector        →  정답 노출 8-pattern LLM 직접 검사 ↺
[Round 5] solve-verifier       →  solve.py ↔ 답안지 정합성 검증     ↺
[Round 6] builder              →  응시자/채점자 PDF · zip · CBT JSON
   │
   ▼
[Output] 30세트 × 3과목 = 90 문제지 패키지 (완전 배포 가능)
```

| 항목 | 스펙 |
|---|---|
| 에이전트 구성 | 오케스트레이터 1 + 전문 에이전트 6 + 스킬 4 |
| 문항 자동 생성 | 그린(AI·엑셀) / 블루(Python·ML) 이중 트랙 |
| 품질 보증 | 정답 노출 패턴 40+개 자동 감지, solve.py 실행 검증 |
| 보안 | 응시자·채점자 트리 분리, 누출 0건 검증 필수 |
| 배포 산출물 | PDF · 첨부 ZIP · CBT JSON · 채점 도구 |

---

## 📐 Architecture Philosophy

```
┌─────────────────────────────────────────────────────────────┐
│                    Orchestrator Layer                       │
│         (라운드 감독 · 재작성 루프 · 사용자 확인)              │
├────────────┬────────────┬────────────┬────────────┬─────────┤
│ Analyzer   │ Designer   │  Writer    │ Verifier   │ Builder │
│ (분류·식별) │ (설계·매핑) │ (문항 작성) │ (검증·루프)  │ (빌드) │
├────────────┴────────────┴────────────┴────────────┴─────────┤
│                     Skills / Domain Knowledge               │
│     exam-authoring · leak-detection · solve-verification    │
│                   · difficulty-tuning                       │
└─────────────────────────────────────────────────────────────┘
```

**핵심 설계 원칙**:
- **LLM이 직접 read** — 정규식 grep으로 잡을 수 없는 의미적 정답 노출 탐지
- **재작성 루프** — 검증 실패 시 해당 라운드로 자동 복귀
- **응시자·채점자 트리 완전 분리** — 채점 자료 누출 0-tolerance

---

## 📊 GitHub Stats

<div align="center">

<img height="160" src="https://github-readme-stats.vercel.app/api?username=shoman2&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=a78bfa&icon_color=a78bfa&text_color=c9d1d9&count_private=true" />
<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=shoman2&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=a78bfa&text_color=c9d1d9&langs_count=8" />

</div>

<div align="center">

<img src="https://streak-stats.demolab.com?user=shoman2&theme=tokyonight&hide_border=true&background=0d1117&stroke=a78bfa&ring=a78bfa&fire=f59e0b&currStreakLabel=a78bfa&sideLabels=c9d1d9&dates=8b949e" />

</div>

---

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=120&section=footer" />

</div>
