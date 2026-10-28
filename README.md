# HCDT Letter Generator

HCDT 학과 서식(A4) 그리드에 맞춘 레터 생성기. `index.html` 한 파일에 서체·로고·라이브러리 모두 포함.

## 그리드
- A4 210 × 297 mm, 상하좌우 여백 14 mm
- 세로 4단 (단 폭 42.5 mm, 간격 4 mm)
- 가로 14행 (행 높이 15.5 mm, 간격 4 mm)

## 배치
| 영역 | 위치 |
|---|---|
| 로고 | Col 1–2 · Row 1 |
| To / 인사말 (10 pt Bold) | Row 3 하단 기준선 67.90 mm |
| To 정보 | Col 1 · Row 4부터 |
| From | Col 1 · Row 7부터 (To + 58.5 mm). To가 길면 한 행(19.5 mm)씩 아래로 |
| 본문 (8/12 pt Roman) | Col 2–4 · Row 4–9, 쪽당 27줄 |
| 맺음말 | 본문 마지막 줄 아래 24 mm 간격(가이드) 뒤, 기준선 = 마지막 줄 + 26.9 mm |
| 서명 이미지 | 서명자 이름 기준선 아래 한 줄(4.23 mm), 최대 42.5 × 15.5 mm(1단 × 1행), 비율 유지 |
| 연락처 (Email · Tel · Mobile · Fax · Web) | 주소 아래 한 줄 띄우고, 라벨 + 탭 정렬. 빈 칸은 인쇄 안 됨, × 로 삭제 |
| 쪽번호 (8 pt Bold) | 오른쪽 여백 끝, 기준선 16.34 mm |
| 패턴 | Row 13–14, 재단 밖까지 |

## 배포
main 브랜치에 push → GitHub Actions가 GitHub Pages로 자동 배포.
