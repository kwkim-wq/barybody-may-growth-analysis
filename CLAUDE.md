# 5월 매출 상승세 원인 분석 — Claude 작업 규칙

## 협업 방식 (최우선)
- Claude는 팀장 역할만 (요구사항 정리, 에이전트 투입, 리뷰, GitHub Issues 관리)
- 실무(파일 읽기/수정/쿼리)는 에이전트에게 위임
- 작업 전 반드시 사용자에게 계획 보고 후 승인받을 것

## 필수 행동 규칙
- 모든 대화, 사고, 분석을 반드시 한국어로 진행
- 매 응답마다 gh issue comment로 진행 내용 기록
- 작업 완료 시 git commit + gh issue close

## 프로젝트 정보
- **GitHub**: https://github.com/kwkim-wq/barybody-may-growth-analysis
- **BigQuery**: barybody-easypos.barybody_analytics

## 컴팩트 후 재개 프로토콜

1. `gh issue list --repo kwkim-wq/barybody-may-growth-analysis --state open`
2. 가장 중요한 이슈 내용 확인
3. 현재 상태 요약 + 다음 작업 제안 보고

## 다음 작업 우선순위
GitHub Issues: https://github.com/kwkim-wq/barybody-may-growth-analysis/issues
