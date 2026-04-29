# 한일경어변환기 — 日韓 敬語 Converter

> 한국어 ↔ 일본어 경어를 AI로 변환하는 웹 앱  
> AI-powered Korean ↔ Japanese Keigo Converter

[![Copyright](https://img.shields.io/badge/Copyright-2026%20여은혜-red.svg)](#제작자)
[![Made by](https://img.shields.io/badge/Made%20by-Eunhye%20Yeo-gold.svg)](#제작자)

---

## ✨ 주요 기능

- 한국어 → 일본어 / 일본어 → 한국어 **양방향 변환**
- 경어 레벨 **5단계** (반말 → 극존칭)
- 상황별 선택 (대면 / 메시지 / 이메일 / 공문서)
- **음성 재생** + 단어·묶음 클릭으로 원하는 지점부터 재생
- **발음 표기** — 히라가나 읽기 / 한국어 발음 / 가타카나 발음
- 번역 횟수 카운터 (오늘 / 누적)

---

## 🚀 사용 방법

1. [OpenRouter](https://openrouter.ai) 에서 무료 API 키 발급
2. 앱 상단 ⚙️ **API Key 설정** 클릭 후 키 입력 및 저장
3. 변환할 문장 입력 (한국어 또는 일본어 자동 감지)
4. 상황·경어 레벨 선택 후 **変換 · 변환하기** 클릭

---

## 🌐 바로 사용하기

```
https://siriayeo-crypto.github.io/yeoeunhye/keigo/
```

---

## 🛠 기술 스택

| 역할 | 기술 |
|---|---|
| 프론트엔드 | HTML / CSS / JavaScript (순수 웹) |
| AI 번역 | OpenRouter API — Gemini 2.0 Flash |
| 음성 재생 | Web Speech API (브라우저 내장) |
| 데이터 저장 | localStorage |

---

## 📁 파일 구조

```
keigo/
├── index.html   # 앱 본체
├── README.md    # 소개 문서
└── LICENSE      # 저작권 고지
```

---

## ⚠️ 저작권 및 라이선스

**Copyright 2026. 여은혜. All rights reserved.**

이 소프트웨어의 소스 코드와 디자인에 대한 모든 권리는 저작권자 **여은혜**에게 있습니다.

- ✅ 개인적인 학습, 연구, 코드 리뷰 목적의 열람 허용
- ✅ 개인적인 용도로 로컬 환경에서 실행 허용
- ❌ 저작권자의 서면 동의 없는 **상업적 이용 금지**
- ❌ 수정·재배포하여 별도 서비스로 제공하는 행위 금지
- ❌ 저작권 표시 삭제 또는 변경 금지

자세한 내용은 [LICENSE](./LICENSE) 파일을 확인하세요.  
문의: yeoeh525@gmail.com

---

## 👤 제작자

**여은혜 (Eunhye Yeo)**

- 이벤트 기획 전문가 · 18년 F&B·공연·MICE·브랜드 팝업 운영
- 한국어 · 日本語(N1) · English
- Designed, planned & developed by Eunhye Yeo

---

*이 앱은 비즈니스 현장에서 실제로 필요한 경험을 바탕으로 기획되었습니다.*
