# AI_HealthCare

🏋️ HealthHub AI

개인 맞춤형 헬스 기록 & AI 건강 관리 플랫폼

HealthHub AI는 체중, 운동, 건강 지표, 식단을 하나의 플랫폼에서 통합 관리하고
AI를 활용해 개인 맞춤형 분석과 식단 추천을 제공하는 헬스 기록 웹 애플리케이션입니다.

기록에 그치지 않고, 분석 → 피드백 → 행동 유도까지 연결하는 헬스 파트너를 목표로 합니다.

🔗 Demo & Docs

🌐 Web URL:

📊 PPT 기획안:

✨ 핵심 기능
👤 회원 관리

이메일 기반 회원가입 / 로그인

개인별 건강 데이터 분리 관리

목표(감량 / 유지 / 증량) 기반 서비스 제공

📊 대시보드

최근 체중 및 BMI 상태

목표 체중 대비 진행률

오늘 운동 여부 및 건강 요약

그래프 기반 직관적 시각화

⚖️ 체중 & BMI 관리

날짜별 체중 기록

BMI 자동 계산

체중 변화 추이 그래프

🏃 운동 플래너 & 캘린더

운동 계획 + 수행 여부 관리

MET 기반 소모 칼로리 자동 계산

캘린더 기반 운동 지속성 시각화

🩺 건강 지표 기록

혈압 / 혈당 / 수면 시간 관리

일 단위 기록 및 장기 데이터 축적

🤖 AI 맞춤 식단 추천

신체 정보 + 목표 기반 자동 식단 생성

BMR / TDEE 계산

OpenAI API 활용

JSON 형태 결과 저장 및 이력 관리

🧠 서비스 컨셉

All-in-One 헬스 관리

기록 → 분석 → 피드백 → 행동 유도

AI 기반 개인 맞춤화

초보자 친화적 UI / 시각적 피드백 중심

🛠 기술 스택
Frontend

React + TypeScript

Vite

Tailwind CSS

Recharts

Backend

Python Flask

MySQL

REST API

AI

OpenAI API

GPT 기반 식단 추천

🗄 데이터베이스 구조 (요약)

users

weight_records

workout_records

health_metrics

meal_logs

모든 데이터는 users 테이블을 중심으로 1:N 관계로 연결되며
외래키 + ON DELETE CASCADE를 통해 데이터 무결성을 보장합니다.

🚀 향후 확장 계획

웨어러블 디바이스 연동

AI 운동 루틴 추천

장기 건강 리포트 자동 생성

의료 데이터 연계

🎯 프로젝트 목표

HealthHub AI는
“기록에서 끝나는 헬스 앱”이 아니라
사용자의 행동을 변화시키는 AI 헬스 파트너를 지향합니다.
