# 🌺 Aloha Shopping

하와이 여행 쇼핑리스트 PWA 앱

## 기능
- 📷 아이템 사진 추가 (카메라/갤러리)
- 📝 이름 + 메모 관리
- ✅ 체크/완료 표시
- 📱 PWA - 홈 화면 설치 가능
- 🔌 오프라인 동작

## 배포

GitHub Pages에서 바로 호스팅 가능합니다.

1. 이 레포의 Settings → Pages
2. Source를 `main` 브랜치, `/ (root)` 선택
3. Save

## 파일 구조
```
├── index.html      # 메인 앱 (HTML/CSS/JS 올인원)
├── manifest.json   # PWA 매니페스트
├── sw.js           # Service Worker (오프라인 캐싱)
├── icon.svg        # 파비콘
├── icon-192.png    # PWA 아이콘
└── icon-512.png    # PWA 아이콘 (스플래시)
```
