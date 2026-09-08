# Sinsunhan (신선한)

[Zittme](https://github.com/zittme/zittme) 엔진용 공식 쇼핑몰 테마입니다. 식품·생활 쇼핑몰을 위해 첫 화면부터 상품과 기획전이 주인공이 되도록 구성했고, 깊은 송엽 그린과 아이보리 바탕으로 신선함을 담았습니다. 레이아웃과 커머스 · 게시판 · 회원 · 쪽지 · 알림센터 · 메시지 · 예약 · 짓미페이 · 문의 · 지식질문 스킨이 한 벌로 맞춰져 있습니다.

- 데모: https://shopdemo.zitt.me (관리자 데모 계정으로 관리 화면까지 볼 수 있습니다)
- 스토어: https://zitt.me/store/package/33949

## 요구 사항

- Zittme 1.0.0 이상
- [commerce](https://github.com/zittme/commerce) 0.2.17 이상 권장. 커머스 · 예약 · 짓미페이 · 문의 · 지식질문 등 부가 모듈 스킨은 해당 모듈이 설치된 사이트에서만 적용됩니다.

## 설치

Zittme 설치 경로의 `themes/sinsunhan` 에 이 저장소의 내용을 놓습니다. **폴더 이름은 `sinsunhan`** 입니다.

```bash
cd 설치경로/themes
git clone https://github.com/zittme/theme-sinsunhan.git sinsunhan
```

압축 파일로 받았다면 `themes/sinsunhan/` 에 풀면 됩니다. 이후 관리자 > 테마에서 신선한을 적용하면 레이아웃과 스킨이 한 번에 바뀝니다.

## 구성

- 레이아웃 `sinsunhan`: 검색 중심 헤더와 장바구니 뱃지, 비주얼 슬라이더(문구 정렬 선택), 카테고리 타일(아이콘 이미지 지정 가능), 일일특가 · 기획전 · 추천 · 랭킹 · 신상품 · 할인 상품 등 메인 구성 블록, 모바일 하단 탭바
- 모듈 스킨 `sinsunhan`: 커머스 · 게시판 · 회원 · 쪽지 · 알림센터 · 메시지 · 예약 · 짓미페이 · 문의 · 지식질문
- 커머스 스킨: 안내문 HTML, 배너 포인트 이미지 정렬, 주문내역·장바구니 링크와 검색창 표시 설정, 주문 상태 필터를 지원합니다

## 라이선스

[GPL v2](LICENSE)

## 문의

- 홈페이지: https://zitt.me
- 매뉴얼: https://zitt.me/manual
