# UGC 리뷰 영상 제작 사양서

## 개요
- **유형:** 토킹헤드 리뷰 UGC (ugc-review-video)
- **제품:** 126cm 초대형 3단 자동 우산 (extra-large 3-fold automatic umbrella)
- **길이:** 15초 (9:16 세로) · 보드 1장 (FULL_ARC) · 8개 내부 하드컷
- **언어/톤:** 영어(미국식 액센트) · NATURAL 톤(따뜻하고 자연스러운 크리에이터)
- **음악:** 없음 (기본)

## 크리에이터
- 힉스필드 학습 캐릭터 `dreo-ugc-01` (20대 초반 한국 여성 UGC 인플루언서)
- Soul V2 id: `9d3ec726-de99-43e5-b612-b1a82f8cef1d`
- 보드/클립용 character_media_id(import): `08d20338-3342-4059-bd83-b5598c0bcfe1`

## 제품 레퍼런스
- product_reference(media_id): `ba12be30-3992-4d1d-bd63-59763d1203dc` (가장 최근 업로드)
- Angle Lock 적용 (@Image1 정면만 사용)

## 클레임 처리 (중요)
- 승인된 클레임 목록 **없음** → 눈에 보이는 물리적 특징만 사용
- 사용: 접으면 작게 접힘 / 한 손 자동 개폐 버튼 / 펼치면 큰 캐노피 / 다시 빠르게 접힘
- **제외:** "판매 1위", "차단율 99.9%", "126cm" 등 수치·비교·성능 주장 (승인 목록 없으면 금지)
  - 필수 수치/문구가 있으면 approved_claims로 제공 시 반영 가능

## 스토리 구조 (8슬롯 FULL_ARC)
1. HOOK (셀피, MID) — 접힌 우산을 들고 "봐봐" 리액션
2. 컨텍스트 (스태틱, WIDE) — 얼마나 작게 접히는지
3. 라이프비트 (스태틱, MACRO) — 손바닥 위 접힌 우산, 자동 버튼 위치
4. 첫 터치 (셀피, TIGHT) — 엄지로 버튼 누르기 직전
5. 코어 리빌 (스태틱, MID) — 캐노피가 활짝 펼쳐짐 (피크 바디 이벤트)
6. 매크로 디테일 (스태틱, MACRO) — 팽팽한 캐노피 원단/살
7. 결과 (스태틱, WIDE) — 큰 우산 아래 어깨·가방까지 덮임
8. 추천 마무리 (셀피, TIGHT) — 따뜻한 미소, 다시 접힘 (루프)

## 파이프라인 상태
- [x] 폴더/브랜치, 크리에이터, 제품 확정
- [x] 레퍼런스 확보, 캐릭터 import
- [x] 스토리보드(gpt_image_2) 생성 → 리얼리즘 보정(seedream)
- [x] 사용자 확인 체크포인트 (제품/캐릭터)
- [x] 클립(seedance_2_5, 네이티브 음성) 생성
- [x] 최종 9:16 MP4 (N=1이라 단일 클립이 최종본)

## 최종 결과물
- **영상(피부 보정본 · 최종):** https://d2ol7oe51mr4n9.cloudfront.net/user_33rbzRvWV0ZVyLjMopqDKCxOile/88dda3dc-b520-4302-90da-0f48ef6bd302.mp4
  - 기존 렌더링본에 ffmpeg 스킨 스무딩(hqdn3d + smartblur + eq) 후보정으로 잡티 완화 (크레딧 미사용)
- 영상(원본 렌더링): https://d8j0ntlcm91z4.cloudfront.net/user_33rbzRvWV0ZVyLjMopqDKCxOile/hf_20260912_041033_d2ad7ff5-4c7f-4536-8b80-f20e80c932a6.mp4
- 보드(리얼리즘 보정): https://d8j0ntlcm91z4.cloudfront.net/user_33rbzRvWV0ZVyLjMopqDKCxOile/hf_20260912_040553_381a2782-2636-47d5-9029-d0dacd550603.png
- 보드(깨끗한 피부 보정 · 재렌더용): https://d8j0ntlcm91z4.cloudfront.net/user_33rbzRvWV0ZVyLjMopqDKCxOile/hf_20260912_042722_fe2954fc-409d-4578-9453-b6ae2fd3cd32.png

## 메모
- 크레딧 부족으로 깨끗한-피부 보드(fe2954fc) 기반 영상 재렌더링은 보류. 크레딧 충전 시 최고 품질로 재렌더 가능.
- 옵션(미적용): 자막 번인 / 훅 텍스트 / 포스트 패키지(캡션·해시태그·광고 고지)
