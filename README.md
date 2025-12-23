# 📊 정책동향 자동 보고서 시스템

이 시스템은 **코딩을 전혀 몰라도**
매일 자동으로 정책동향을 정리해
이메일로 보내주는 자동 보고서입니다.

---

## 🔍 이 시스템은 무엇을 하나요?

1. 정부 정책뉴스 자동 수집  
2. AI가 핵심 내용 2줄 요약  
3. 주요 키워드 정리  
4. 보고서 자동 생성  
5. 이메일 자동 발송  

👉 사용자가 할 일은 **없습니다**

---

## 🧑‍💼 이런 분께 추천합니다

- 정책·기획·전략 담당자
- 공공기관·연구기관
- 매일 정책뉴스 정리하는 분

---

## 🚀 처음 한 번만 설정 (약 10분)

### 1️⃣ GitHub 계정 생성
https://github.com

### 2️⃣ 새 저장소 생성
- New repository
- 이름: policy-news-auto

### 3️⃣ 이 프로젝트 파일 전체 업로드

---

## 🔐 4️⃣ 비밀키 입력 (중요)

Settings → Secrets and variables → Actions

| 이름 | 입력할 내용 |
|----|------------|
| POLICY_NEWS_SERVICE_KEY | 정책뉴스 OpenAPI 키 |
| MISTRAL_API_KEY | AI 요약 API 키 |
| GMAIL_ADDRESS | 보내는 Gmail |
| GMAIL_APP_PASSWORD | Gmail 앱 비밀번호 |
| TO_EMAIL | 받는 이메일 |

⚠️ 입력한 값은 화면에 보이지 않는 것이 정상입니다.

---

## ▶ 실행 방법

### 지금 바로 실행
Actions → Policy News Automation → Run workflow

### 자동 실행
- 매일 **오전 9시 자동 실행**
- 컴퓨터 꺼져 있어도 작동

---

## 📬 결과
- 입력한 이메일로
- 정책동향 보고서 자동 수신

---

✔ 코딩 필요 없음  
✔ 자동 실행  
✔ 이메일 수신
