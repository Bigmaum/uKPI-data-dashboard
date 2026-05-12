# uKPI Data Dashboard

대학알리미(academyinfo) 공시DATA 수집 현황을 시각화한 정적 HTML 대시보드.

## 보기

**https://bigmaum.github.io/uKPI-data-dashboard/**

또는 [dashboard.html](dashboard.html) 직접 열기.

## 내용

- KPI × 연도 매트릭스 (수집/미수집)
- 수집 통계 (파일 수, 학교 수, long-format 행 수)
- 카테고리별 KPI 분포 (학생/교육연구성과/대학재정/교육여건/대학운영)
- KCUE 공시 일정 및 데이터 소스 정보

## 데이터 원본

- 출처: [대학알리미 (KCUE)](https://academyinfo.go.kr)
- 수집 범위: 대학 (`schl_div_cd=02`)
- 연도: 2023~2026 (KPI별로 다름)
- 75 KPI 메타 / 72개 다운로드 가능

## 갱신 주기

KCUE 정기공시 사이클(4월·6월·8월·10월) 직후 수집 → 본 대시보드 갱신.

## 소스 (private)

수집 스크립트·아키텍처·운영 절차는 별도 private repo에서 관리.

본 repo는 외부 공개용 정적 시각화만 포함.
