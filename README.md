# K-Soul Food · 포장마차 QR 메뉴

레스토랑 QR 코드를 스캔하면 보이는 모바일 메뉴 페이지.

## 구성
- `index.html` — 메인 페이지 (포장마차 컨셉, 모바일 우선)
- `assets/logo.webp` — K-Soul Food 로고
- `menu-ko.pdf` — 한국어 메뉴 PDF (교체 필요)
- `menu-en.pdf` — 영어 메뉴 PDF (교체 필요)

## PDF 교체 방법
1. 한국어 메뉴 PDF를 프로젝트 루트에 `menu-ko.pdf` 이름으로 저장
2. 영어 메뉴 PDF를 프로젝트 루트에 `menu-en.pdf` 이름으로 저장
3. 커밋 후 푸시하면 끝

## 로컬에서 보기
```
cd ~/k-soulfood
python3 -m http.server 8000
# 브라우저에서 http://localhost:8000 열기
```
