# 그로스마케팅 통합 KPI 대시보드

https://wckmkt.github.io/growth/

퍼포먼스마케팅 + CRM 통합 관점의 고객·채널·코호트 대시보드.

## 이 저장소에 담기는 것

**집계 데이터만** 담는다. 회원번호 등 고객 단위 데이터는 절대 올리지 않는다
(그건 비공개 저장소 `wckmkt/growth-dashboard` 에 있다).

| 파일 | 내용 |
|---|---|
| `index.html` | 대시보드 본체 |
| `growth_cohort_data.json` | 월별 실적 · 코호트 · 등급별 이탈 (집계) |

광고 실적(`pmkt_kpi_data.json`)은 `wckmkt/dashboard` 에서 가져다 쓴다.

## 갱신

비공개 저장소에서 `python publish.py` 로 밀어 넣는다. 직접 편집하지 말 것.
