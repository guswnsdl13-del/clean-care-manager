# THE CLEAN CARE MANAGER V6

V5 기반 업데이트. 기존 localStorage 키 `tcc-manager-v3` 유지.

- 수입지출: 매출과 지출 목록 분리, 지출 주황색 배경, 각각 건수와 총액 표시.
- 홈: 월별(1~12월) 및 연도별(최근 6년) 매출/지출 막대 그래프와 금액 표.
- 매출 그래프는 부가세 포함 거래 합계, 지출 그래프는 지출 거래 총액. 거래일 기준이며 미수금 포함.
- 고객/거래/일정/견적/D-day, 기존 세금계산서 처리 규칙 유지.

## 업데이트
현재 앱에서 전체 백업(JSON) 다운로드 후 ZIP의 index.html, manifest.json, sw.js 파일을 GitHub 저장소 최상위에 업로드하고 Commit changes. 기존 URL 그대로 사용.
