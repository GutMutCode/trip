# Tokyo Trip Planning Notes

도쿄 3박 4일 여행 계획, 장소 후보, 별도 조사 메모를 역할별로 나눈 작업 폴더입니다.

## Folder Map

- `itinerary/` - 실제 여행 실행 계획과 날짜별 동선
- `places/` - 지도 기반 장소 DB, 닫은 장소 아카이브, 쇼핑 후보
- `research/` - 특정 주제별 조사 메모

## Files

### Itinerary

- [도쿄 3박 4일 일정](itinerary/tokyo-3n4d-itinerary.md) - 항공편, 터미널 이동, 날짜별 일정, 귀국 동선

### Places

- [도쿄 Google Maps 지역별 리스트](places/tokyo-google-maps-by-region.md) - Google Maps 공유 리스트를 지역 동선 중심으로 병합한 메인 장소 DB
- [폐업 장소 아카이브](places/closed-places-archive.md) - 메인 장소 DB에서 제외한 폐업 항목
- [도쿄 위스키 숍 후보](places/whisky-shops-tokyo.md) - 위스키/주류 쇼핑 후보

### Research

- [일본 주류 선물 후보 조사](research/japan-alcohol-gifts.md) - 선물용 주류 후보, 가격 감각, 한국 반입 메모
- [체인소맨 애니메이션 성지 위치 조사](research/chainsaw-man-anime-pilgrimage.md) - 일본 내 체인소맨 성지 후보와 동선 메모
- [초카구야공주 애니메이션 성지 위치 조사](research/super-kaguya-princess-anime-pilgrimage.md) - `超かぐや姫！` 성지 후보와 방문 주의 메모

## Organization Rule

- 일정 파일은 확정 정보와 실행 순서만 둡니다.
- 장소 DB는 지역별 후보와 운영시간을 관리합니다.
- 폐업/영업중 후보를 섞지 않고, 닫은 장소는 아카이브로만 보관합니다.
- 조사 파일은 특정 주제별 판단 근거와 출처를 남깁니다.

## Google Maps List Rule

장소 후보를 `places/` 또는 `research/`에 새로 추가할 때는, 일정 파일에 바로 넣지 말고 Google Maps의 비공개 후보 목록에도 함께 저장합니다. 이 목록들은 `itinerary/tokyo-3n4d-itinerary.md`와 분리된 장소 풀로 관리하고, 나중에 필요한 후보를 골라 일정에 반영합니다.

저장할 목록은 장소 성격에 따라 아래 중 하나를 사용합니다.

- `Tokyo Places - Food & Cafe` - 식당, 카페, 디저트, 베이커리
- `Tokyo Places - Shopping` - 편집숍, 백화점, 굿즈, 잡화, 캐릭터/피규어 매장
- `Tokyo Places - Anime Pilgrimage` - 애니메이션 성지, 장면 후보, 촬영/방문 주의가 필요한 성지 후보
- `Tokyo Places - Bars & Liquor` - 바, 위스키/주류 숍
- `Tokyo Places - Sights & Walks` - 전망, 공원, 산책, 랜드마크
- `Tokyo Places - Transit & Logistics` - 공항, 역, 숙소, 이동 거점
- `Tokyo Places - Maybe` - 분류가 애매하거나 일정 반영 여부를 나중에 판단할 후보

추가하지 않는 항목:

- 폐업 장소: `places/closed-places-archive.md`에만 보관합니다.
- 현역 학교, 사유지, 방문 비권장 장소: 조사 메모에는 남길 수 있지만 Google Maps 후보 목록에는 넣지 않습니다.
- 상품/선물 조사처럼 지도상의 방문 장소가 아닌 항목: 직접 저장하지 않고, 필요하면 별도 매장 후보만 `places/`에 정리합니다.
