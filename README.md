# 후쿠오카 · 유후인 여행계획 PWA

2026-11-07 ~ 2026-11-10 일정용 모바일 웹앱입니다.

## GitHub Pages 배포
1. GitHub에서 새 repository를 만듭니다. 예: `fukuoka-trip`
2. 이 폴더의 파일을 repository 최상위에 모두 업로드합니다.
3. GitHub 저장소 → **Settings → Pages** 로 이동합니다.
4. **Build and deployment → Source: Deploy from a branch** 선택
5. Branch를 **main / (root)** 로 선택하고 Save 합니다.
6. 생성된 `https://사용자명.github.io/fukuoka-trip/` 주소를 휴대폰에서 엽니다.
7. Android는 브라우저의 **앱 설치/홈 화면에 추가**, iPhone은 Safari **공유 → 홈 화면에 추가**를 사용합니다.

## 포함 기능
- 4일 일정 요약/상세
- 모바일 일정 추가/삭제
- 일정 순서 드래그(터치) + ↑↓ 대체 버튼
- 카카오맵/구글지도 바로가기
- OpenStreetMap 동선 지도
- 준비물 체크리스트
- Open-Meteo 여행일 날씨
- 예산 및 지출 관리
- 예약번호 및 예약화면/QR 이미지 IndexedDB 저장
- 음식점 우선순위(꼭 가기/시간되면/후보)
- 카카오톡 등 휴대폰 공유 메뉴 호출(Web Share API)
- PWA 설치 및 앱 셸 오프라인 캐시

## 비용
- GitHub Pages: 무료 공개 저장소 기준 사용 가능
- OpenStreetMap/Leaflet: 별도 API 키 없음
- Open-Meteo: 별도 API 키 없음
- 서버/DB: 사용하지 않음

## 데이터 주의
편집한 일정, 예산, 예약 이미지 등은 사용자 브라우저에만 저장됩니다. 브라우저 데이터 삭제 또는 다른 기기 사용 시 자동 동기화되지 않습니다.
