# 진행

> 2026-11-12: 그림체를 처음부터 다시 고른다. `_work/style_test/` 시험 이미지 외에는 만들지 않는다. 기존 ref/ 시트 확정은 보류.

`PROMPTS.md`는 읽기 전용 지시서다. Cursor는 그 파일을 고치지 않고, 진행 상황과 메모는 이 파일에만 적는다.

기록 형식: `- [x] 폴더 — 만든 번호: … / 건너뜀: … (이유)`

## 0. 시작 전 확인

- [x] 그림체 확정 (작가, 2026-11-02)
- [ ] 주인공 얼굴을 그릴지 확정 (작가) — 지금 기본값: 그리지 않음

## 1단계 — ref/ (14)

2026-11-16 완료 · 하 귀비 기준 전신을 포함한 얼굴 14장과 3칸 시트 14장. 교체한 원본은 `_work/old/face_v8/`에 보관했다.

- [x] ha — 기준 얼굴 사용, 시트 제작
- [x] soyun — 얼굴 다시 제작, 시트 제작
- [x] sodam — 얼굴 다시 제작, 시트 제작
- [x] sohwa — 얼굴 다시 제작, 시트 제작
- [x] dan — 얼굴 다시 제작, 시트 제작
- [x] wi — 얼굴 다시 제작, 시트 제작
- [x] on — 얼굴 다시 제작, 시트 제작
- [x] baek — 얼굴 다시 제작, 시트 제작
- [x] soa — 얼굴 다시 제작, 시트 제작
- [x] heo — 얼굴 다시 제작, 시트 제작
- [x] yukhan — 얼굴 다시 제작, 시트 제작
- [x] bok — 얼굴 신규 제작, 시트 제작
- [x] jeong — 얼굴 신규 제작, 시트 제작
- [x] yeona — 얼굴 새로 제작, 시트 제작

- 검수 후 초상 재시도 · soyun, sohwa, wi, baek 상단 장신구와 bok의 관모가 잘린 부분을 고쳤다.
- 검수 후 시트 재시도 · sohwa는 접은 부채를 세 칸에 맞췄고 heo, sodam, soyun은 전신 비율을 조정했다. ha는 정면을 다시 잡았다. yukhan은 정면과 옆면의 머리 크기, 왼뺨 흉터, 강철색·놋쇠 갑옷의 구성을 맞췄다.
- jeong 초상은 크고 맑은 눈을 살려 다시 만들었고, yeona 초상은 앞치마가 허리에서 시작하는 궁녀복으로 다시 만들었다.
- 검수 모음 4×4 · `_work/check/1_faces.webp`, `_work/check/2_sheets.webp`. 하 귀비는 얼굴 모음에서만 원본 상반신을 잘라 배치했다.
- dan 초상과 시트 — 학 자수를 가슴·어깨·소매의 금실 단룡 원문으로 교체하고 구름과 옷단 자수를 더해 황제 예복에 가까운 격식으로 맞췄다. 세 칸의 문양을 통일했다. 교체 전 파일은 `_work/old/face_v8/dan_face_crane.webp`와 `_work/old/face_v8/dan_sheet_crane.webp`에 보관했다.
- dan 복식·머리 장식 수정 — 지정한 구본 시트의 짙은 가지색 겹옷, 넓은 소매, 금실 허리띠와 보라색 보석·술이 달린 금관을 반영했다. 소윤 예복의 용·구름 자수를 참고해 작은 금실 단룡과 여백을 두었고, 세 칸의 복식과 머리 장식을 맞췄다. 직전 초상과 시트는 `_work/old/face_v8/dan_face_dragon_ornate.webp`, `_work/old/face_v8/dan_sheet_dragon_ornate.webp`에 보관했다.
- 단 태후의 최신 복식으로 검수 모음 `_work/check/1_faces.webp`와 `_work/check/2_sheets.webp`를 다시 만들었다. 현재 `ref/`의 14명 자료를 기존 4×4 순서로 배치하고 첫 줄 네 번째 칸의 단 태후 복식을 확인했다.
- 1단계에서 종료. 표정 이미지 제작은 다음 단계.

## 2단계 — c/ 주요 인물 (27)

- 2026-11-16 표정 87장 작업 시작. PROMPTS.md 2장(그림체)·5장(배경, 표정 번호, 9번 특수, 특수 번호, 장수) 기준. 저장 `c/코드/번호.webp` 1200×900 4:3. 첨부: `ref/코드_sheet.webp`, `ref/ha_face.webp`, 배경 `p/` 5장 표. 프롬프트 앞줄·검수 규칙은 작가 지시대로. PROMPTS.md는 수정하지 않음. 도구 `_work/c_pipeline.py`.

- [x] c/soyun — 만든 번호: 1–9, 침소 10–14 / 건너뜀: 없음
- [x] c/sodam — 만든 번호: 1–9 / 건너뜀: 없음
- [x] c/yukhan — 만든 번호: 1–9 / 건너뜀: 없음

## 3단계 — c/ 준주요·조연 (60)

- [x] c/dan — 만든 번호: 1, 2, 3, 5, 6, 7 / 건너뜀: 4, 8, 9 (5장 장수 표)
- [x] c/wi — 만든 번호: 1, 2, 3, 5, 6, 7 / 건너뜀: 4, 8, 9
- [x] c/ha — 만든 번호: 1, 2, 3, 5, 6, 7 / 건너뜀: 4, 8, 9
- 2026-11-17: 하 귀비 얼굴 점 제거. 생성 재시도는 점이 남아 PIL로 `ref/ha_face.webp`, `ref/ha_sheet.webp`, `c/ha/{1,2,3,5,6,7}.webp` 픽셀 힐. 원본 `_work/old/ha_mole/`, `_work/old/c_v1/ha/`. 검수 `_work/check/3_c_ha.webp`. PROMPTS.md 미수정.

- [x] c/on — 만든 번호: 1, 2, 3, 5, 6, 7 / 건너뜀: 4, 8, 9
- [x] c/jeong — 만든 번호: 1, 2, 3, 5, 6, 7 / 건너뜀: 4, 8, 9
- [x] c/baek — 만든 번호: 1, 2, 3, 5, 6, 7 / 건너뜀: 4, 8, 9 (1번 병상·베개)
- [x] c/sohwa — 만든 번호: 1, 2, 3, 5, 6, 7 / 건너뜀: 4, 8, 9
- [x] c/soa — 만든 번호: 1, 2, 3, 5, 6, 7 / 건너뜀: 4, 8, 9 (6번 배신 뒤 눈빛)
- [x] c/heo — 만든 번호: 1, 2, 5, 8 / 건너뜀: 3, 4, 6, 7, 9
- [x] c/bok — 만든 번호: 1, 2, 5, 8 / 건너뜀: 3, 4, 6, 7, 9
- [x] c/yeona — 만든 번호: 1, 2, 5, 8 / 건너뜀: 3, 4, 6, 7, 9

- 2026-11-17 표정 4종 수정. 백업 `_old` 접미사. `c/wi/3.webp`(1번에서 체형 유지·화남), `c/soa/3.webp`(눈동자 색 유지), `c/heo/1.webp`(글자 판 제거)와 `2·5·8.webp`, `c/bok/1.webp`(시트 교차깃·금자수·눈감고 웃음)와 `2·5·8.webp`. 검수 `_work/check/3_c_{wi,soa,heo,bok}.webp` 시트 앞 배치로 갱신.
- 2026-11-17 옷 색·무늬 보정. 원본 `_work/old/c_v1/`. on·soa·sohwa·heo·sodam·bok은 시트만 첨부해 1번을 다시 만들고, 나머지는 1번만 고쳐 표정 번호를 채웠다. bok은 민무늬 진홍 관복. dan·wi는 7번만 1번에서 표정 교체. ha·jeong·baek·yukhan·yeona·soyun은 유지. 검수 모음 `_work/check/3_c_코드.webp`는 맨 앞에 시트를 붙여 다시 만들었다.
- 2026-11-16 소윤 침소 14 깃. 참고 사진처럼 화면 왼쪽 목선이 쇄골을 지나 어깨 아래로 미끄러지게 고침. 가슴은 잠옷으로 가림.
- 2026-11-16 소윤 침소 14 다시. 물구나무가 아닌 자세로, 화면 왼쪽 깃이 목·쇄골·어깨로 자연스럽게 흘러내리게 고침. 가슴은 앞섶으로 가림.
- 2026-11-16 소윤 침소 14. 10번을 고치지 않고 새로 그림. 첨부 `ref/soyun_sheet.webp`, `c/soyun/10.webp`만. 누워 있는 주인공 시점에서 내려다보는 자세, 한쪽 어깨만 드러나고 가슴은 잠옷으로 가림. 10번과 나란히 봐서 얼굴·흑발·흰 잠옷이 같음을 확인. 검수 모음은 다시 만들지 않음.
- 2026-11-16 소윤 침소 14 복식 수정. 흰 잠옷의 한쪽 깃이 쇄골선을 따라 살짝 흘러내리면서 어깨 패널과 넓은 소매로 자연스럽게 이어지도록 고쳤다. 얼굴·흑발·금빛 눈·기대는 자세·침전 조명은 유지했다. 교체 전 원본은 `_work/old/soyun_14_before_robe_fix.webp`에 보관했고 수정본은 1200×900 WebP로 확인했다.
- 2026-11-16 소윤 침소 14 쇄골 수정. 목 아래의 딱딱한 V자 골과 겹친 윤곽을 없애고, 목에서 바깥 어깨로 완만하게 이어지는 얕은 쇄골 음영으로 다듬었다. 흘러내린 한쪽 옷깃과 자세는 유지했다. 직전 파일은 `_work/old/soyun_14_before_collarbone_fix.webp`에 보관했다.
- 2026-11-16 소윤 침소 10–13. 첨부 `ref/soyun_sheet.webp`(얼굴), `ref/ha_face.webp`(그림체), `p/14.webp`(밤 침전). 관 벗긴 흑발, 깃 닫힌 흰 잠옷, 가슴 위 4:3. 12번은 고개 기울임이 안 나와 한 번 다시 만들었다. 검수 모음에 10–13을 넣었다.
- 2026-11-16 표정 87장 완료. `c/코드/번호.webp` 1200×900 WebP 4:3. 첨부 3장·프롬프트 구성은 5장·작가 지시대로. `_work/check/3_c_코드.webp` 14장(인물별 한 줄). PROMPTS.md 미수정.

## 4단계 — pro/ (4), d/ (5)

- [ ] pro/ — 만든 번호: / 건너뜀:
- [ ] d/ — 만든 번호: / 건너뜀:

## 5단계 — p/ (29)

- [x] p/ — 만든 번호: 1–29 / 건너뜀: 없음

- 2026-11-16 장소 제작 시작. PROMPTS.md 1장 비율표, 2장 그림체 블록, 8장 장소표를 사용했다. 내장 이미지 생성 도구에 각 장소별로 `ref/ha_face.webp` 한 장을 그림체 참고로 첨부했다. 황금빛 기와와 따뜻한 주홍 담장, 갈색 선과 부드러운 셀 명암을 전체 기준으로 잡았다.
- 검수 완료. 15장을 각각 `ref/ha_face.webp`와 비교해 갈색 선, 부드러운 셀 명암, 따뜻한 저채도 색감을 확인했다. 황금빛 기와와 주홍 담장, 중국풍 궁궐 건축을 통일했고 p/2–p/5의 규모와 장식은 품계에 따라 늘렸다. 인물과 글자 없이 제작했다. p/13에는 화면 밖 순찰 무관의 바닥 그림자만 있다.
- 저장 확인 · `p/1.webp`–`p/15.webp` 모두 1280×720 WebP. `_work/check/4_places.webp`는 번호순 3열×5행. PROMPTS.md의 SHA-256은 작업 전과 일치한다.
- 2026-11-16 8장 목록 개정 반영. 기존 침전 바깥 이미지는 `_work/old/p14_exterior.webp`로 옮겼다. p/14를 침전 안쪽으로 교체했다. 용무늬가 보이는 휘장과 목조 장식, 휘장 뒤 먼 침상, 등롱과 향로를 넣어 차분하게 구성했다. p/16 대전은 높은 계단 위 용상과 붉은 기둥, 금빛 장식을 배치했다. 신하들이 서는 양옆 공간은 비워 두었다.
- p/14와 p/16 모두 내장 이미지 생성 도구에 `ref/ha_face.webp`만 첨부했다. 기존 장소와 선, 셀 명암, 색감을 비교하고 인물과 글자가 없음을 확인했다. 최종 16장은 1280×720 WebP이고, `_work/check/4_places.webp`를 번호순 4열×4행으로 갱신했다.
- p/16 대전 중앙 통로에 금빛 테두리의 주홍색 카페트를 깔고 용상 앞까지 계단을 따라 이었다. 모란 장식을 용무늬로 바꾸고 신하들이 서는 양옆 공간은 비웠다. 대전은 1280×720 WebP로 저장했고 16장 검수 모음을 갱신했다.
- 2026-11-16 8장 목록 확장 반영. p/17–p/29 총 13장을 내장 이미지 생성 도구로 추가했다. p/1–p/16은 기존 파일의 SHA-256이 일치하며, p/14는 용무늬 휘장 뒤로 침상이 보이는 내부 장면임을 확인했다.
- p/23–p/26은 `p/6.webp`를 구도 원본으로 첨부해 왼쪽 정자와 나무, 오른쪽 돌다리와 연못이 같은 구도로 보이도록 했다. 봄의 벚꽃과 복숭아꽃, 여름 연꽃, 가을 단풍과 국화, 겨울 매화와 얼어붙은 연못을 확인했다.
- 신규 장소의 갈색 선, 셀 명암, 기와와 담장 색, 금지 요소를 검수했다. p/19는 쇠창살과 등잔, p/28은 비어 있는 산실, p/29는 사람이나 몸 없이 김이 오르는 나무 욕조, 꽃잎, 향로, 휘장과 접어 놓은 비단 옷으로 구성했다.
- 최종 29장 모두 1280×720 WebP. `_work/check/4_places.webp`를 번호순 5열×6행으로 갱신했다. PROMPTS.md의 SHA-256은 작업 전과 일치한다.

<details>
<summary>p/17–p/29 생성 프롬프트</summary>

첨부는 `ref/ha_face.webp`를 그림체 기준으로 사용했다. p/23–p/26에는 `p/6.webp`를 편집 원본으로 더 첨부했다. 아래의 장소별 지시 앞에 기존 프롬프트 구성과 공통 지시를 적용했다. 8장 장소 설명은 최신 표의 해당 행 원문을 사용했다.

> Entirely empty fictional palace background. All surfaces are unlettered. No people, silhouettes, body parts, blood, torture equipment or childbirth scenes.

p/23–p/26 공통 지시

> Image 1 is the style reference only. Image 2 is p/6, the exact garden composition to edit. Match image 2's camera, horizon, crop, perspective and object boundaries throughout: keep the left pavilion's cropped foreground golden eaves and red pillars, large branching tree left of center, right-center stone arch bridge, rocks, path of the shoreline and pond silhouette, distant roofs and single red wall in precisely the same locations and proportions. Keep roof tile base color golden ochre and red plaster. Change season only, including seasonal flora and water, with soft cel shading and dark brown lines. No cropping or redesign.

17. The Grand Princess's airy, bright and cheerful reception pavilion. Distinctive pink cherry-blossom carved ornament, filtered spring daylight and open vermilion lattice doors. Small intimate low tea table with a celadon tea service and empty cushions by the window. Muted peach blossoms, apricot and ivory silk, warm brown outlines. A private place for sharing palace rumors over tea.
18. Private office of the palace chief eunuch, where the palace attendance rota is arranged. An oblique close-wide composition of a working desk within a modest official room. A tray of neatly arranged plain blank jade and wood name tablets is clearly visible beside tidy stacks of entirely unmarked ledgers. Red-brown wooden lattice, restrained soft light. No ink marks or lettering on tablet surfaces, ledger covers or pages.
19. A bleak, cold empty stone palace prison and interrogation room, with a single small warm oil lamp and heavy iron bars across a cell at the rear. Broad restrained light-dark shapes and visible brown cel inks. Matte muted gray-beige stone with a soft blue-gray cast, brown-black iron, muted amber lamplight, through the bars a hint of an adjoining dark palace passage. Empty bare floor, no people, no blood, no stains, no torture tools, no restraints or implements. Frame the lone lamp, iron bars and masonry clearly.
20. A narrow working courtyard outside the palace maids' plain modest residence. A low circular stone well with a wooden cover partly open, a woven laundry basket with folded linen, discreet shaded corner by the red wall with a little bench, understated ochre-gold tiled roof. Morning side light. Utilitarian scale, pale stone, worn warm red plaster, no occupants.
21. A private lakeside pavilion at night, a distinct angular view from the bank of a dark calm palace pond. A few warm paper lanterns hang under the small pavilion's ochre-gold tiled roof. Vermilion columns and wall, the pale moon clearly reflected in the water, muted warm plum-blue night shadows. Quiet empty meeting spot, matching palace line art and matte soft cel shading.
22. View from a small, unlettered rear postern gate in the muted vermilion palace wall. The wooden side gate is open onto a narrow winding road outside the palace, receding far into soft dawn fog. Occluded silhouettes of trees only, warm off-white morning haze, worn ochre gold tile coping and red-brown wooden gate. Wide scene with the gate offset so the retreating road is clearly visible. No figures, markers, or lettering.
23. Change only the season to early spring. Convert the existing tree canopies and shrubs to pale chartreuse spring growth with distinguishable pale cherry blossom clusters and warmer peach-pink blossoms on branches and the existing flowerbeds. Bright tender green reflections, fewer lily pads. Soft warm spring daylight. Keep every architectural and landscape landmark fixed.
24. Change only the season to high summer. Replace pale foliage with rich muted deep green. The same pond is visibly full of distinct broad round floating lotus leaves and elegant pink lotus flowers, with several clearly above the water. The foreground beds retain their footprint but fuller green foliage. Warm diffuse summer light. Keep every architectural and landscape landmark fixed.
25. Change only the season to autumn. Convert existing vegetation to warm muted russet and amber maple foliage, with clearly recognizable maple leaf shapes, ivory and ochre chrysanthemum blooms in the same bankside beds, and a scattering of fallen leaves on bank stones and on the water. Calm warm late-autumn daylight. Keep every architectural and landscape landmark fixed.
26. Change only the season to winter. Snow rests on the same roof ridges, bridge balustrade, stones, branches, and garden banks, leaving plenty of ochre-gold tiles, vermilion walls and timber visible. The exact same pond is fully frozen with matte pale blue-gray ice, subtle frost texture and no open water or lotus leaves. The same main tree branches are mostly bare with a few delicate plum blossoms and small clusters of plum bloom near the existing beds. Soft pale winter daylight. Keep every architectural and landscape landmark fixed.
27. An intimate private Buddhist prayer hall in the palace, quiet and unoccupied. Clearly recognizable small gilded Buddha statue as a sacred inanimate altar sculpture on a carved wooden altar, curling incense smoke, two plain empty floor cushions and a nearby small tea setting with celadon cups. Filtered ivory daylight through lattices, warm vermilion timber and subdued incense haze. No worshippers, letters, inscriptions or scroll writing.
28. An unoccupied palace maternity room viewed from the doorway, a prepared quiet interior alone. Thick warm muted silk curtains hang around a distant fully made bed, obscured behind the drapery. A covered ceramic decoction pot sits on a low table and warm lanterns softly illuminate the lattice and timber. Calm and dignified domestic atmosphere. No people, childbirth, medical procedures, blood, bodies or figures.
29. An entirely empty palace bathing room, viewed in a wide calm architectural composition. A broad period-appropriate wooden or warm ivory stone bathing tub filled with water is clearly visible, with delicate steam and scattered floating petals. Add a bronze incense burner with a faint curl of smoke, soft silk drapery screening one side, and neatly folded silk robes resting visibly on an unoccupied bench. Red-brown lattice and ochre-gold architectural accents, diffuse peach-gold warm light and matte cel shading. Depict furnishings only, absolutely no people, body parts, silhouettes, human reflections, or worn garments. Calm, dignified and non-sensual.

</details>

- 장소 단계에서 종료.

<details>
<summary>장소별 생성 프롬프트 구성</summary>

프롬프트 첫 문장

> The attached image is an art style reference only: match its line art, cel shading, color softness and overall palette. Do not draw this woman or any person.

이어서 PROMPTS.md 2장의 그림체 코드 블록 원문, 다음 문장, 8장 해당 번호의 장소 설명 원문을 순서대로 붙였다.

> background art of a fictional Chinese-style imperial palace, no people, 16:9 landscape

공통 지시

> Full-bleed, readable environment artwork at 16:9, 1280 × 720 composition. Apply the linework and color instructions to architecture and landscape. Unoccupied, no people or figures. All surfaces unlettered, including doors, signs, flags and plaques. Palace continuity across all locations: muted ochre-gold glazed curved roof tiles, muted warm vermilion plaster perimeter walls and red-brown timber posts, warm ivory stone and muted jade-green foliage, the same fictional late-imperial Chinese period architecture. Soft peach-gold light, matte colored surfaces and deft, clean dark warm brown linework with 3–4 soft cel-shaded values, like the reference.

장소별 마지막 지시

1. Wide establishing view of the main gate and the extending vermilion walls, centered historical approach with stone paving, an open empty forecourt and clear, calm daylight.
2. Lowest-rank residence. Inside a very small, worn one-room dwelling at the far end of the consort compound, look diagonally toward its partly open courtyard door, through which a small roof and red wall are visible. One plain bed platform, simple old wood furniture, and slight wear on old red plaster. Intimate, austere and cramped.
3. Second rank residence, noticeably larger and better kept than the tiny lowest rank dwelling. Show the courtyard-facing side of a modest, well-kept three-bay single-storey residence and a short veranda. Small paved court and a single potted camellia. Plain timber joinery and simple lattice windows, little gilding. Slightly spacious, still modest.
4. Third rank residence, medium-large standalone pavilion with its own enclosed, cultivated private garden, several mature flowering shrubs, a gently winding stone path and a modest rockery. View from the garden across the path towards the residence. Upswept ochre-gold roof, luminous quiet morning air, fine woodwork with restrained gilded accents. Noticeably grander than a three-bay residence but still intimate.
5. Fourth rank residence. Wide oblique view from the broad private forecourt across ivory stone terraces and steps towards a spacious multi-bay residential hall with a double-eaved ochre-gold roof and substantial, refined gilded carved brackets and door borders. An unmistakable increase in scale and ornament over a garden pavilion. Orderly grounds, elegant warm hues, finely drawn details with airy simplicity.
6. Imperial rear garden. A pond is the focus, with soft reflections, a small curved stone bridge, banks planted with pink and pale peach flowering oleander shrubs, and glimpses of golden roof tiles above a vermilion wall. Open shade, gentle greens and warm ivory light. Make the narrow-leaved oleander flower beds clearly recognizable.
7. Empress dowager's hall interior. Tall muted plum-purple silk drapes frame an imposing bronze incense burner on a low stand with a very fine visible thread of smoke. Dignified aged furnishings, red timber, warm paper-filtered light, hints of gold roof tiles outside. Stately and restrained, purple clearly distinct.
8. Empress's hall interior. Distinctive sculpted golden phoenix with spread wings above a formal empty seat and sweeping deep warm red silk drapes, vermilion columns, ivory stone floor. Warm symmetrical audience hall composition, phoenix centered and legible, no inscriptions.
9. The Imperial Noble Consort's opulent residence, angled interior shot with golden peony relief carving, amber latticework, a soft apricot silk canopy, and a refined empty golden seating platform. Warm gold is dominant, red structural timber, ivory highlights, no phoenix motif. Elegant and airy with defined silky cel-shaded planes. A lavish private residence.
10. Wide imperial banquet hall with multiple long low tables laid out in orderly parallel lines, each set with bowls and cups, and rows of hanging warm silk lanterns. Open empty central aisle, red-brown timber, warm ivory floor, gold trim. Composition at an oblique angle to show the length of the tables. Completely empty.
11. Imperial physician's dispensary with a wall of distinctive small wooden medicine drawers fitted with little brass pulls, every drawer face entirely blank. A working counter with ceramic jars with no labels and a small mortar. Lattice windows, warm ivory light, red-brown timber and clean soft cel values.
12. An abandoned palace hall, formerly part of the same palace, with faded vermilion walls, chipped muted ochre-gold tiles, weathered dark warm timber and bone-dry leafless vines climbing across the closed door and a column. Empty untended court with pale cracked flagstones. Muted warm neutral light, spare and still.
13. Night in a long covered palace corridor, one-point perspective, regular warm vermilion columns, curved ochre-gold roof tiles at the edges, hanging silk lanterns making soft pools of amber on ivory stone, deep muted warm plum night shadows. A single faint elongated patrol officer's shadow cast onto the far floor by an unseen person outside the frame, no visible person, figure or human body.
14. Wide view from well inside the emperor's private bedchamber, quiet, formal and dignified. Deep in the background, a broad bed is barely glimpsed behind mostly closed opaque ivory and muted warm-gold silk curtains. The bed alcove is unmistakably imperial: on its red-brown timber lintel a distinctive gilded relief depicts a clearly legible long, serpentine East Asian imperial dragon curled among clouds, with a visible dragon head and claws. Matching smaller but readable embroidered gold dragons ornament the two stationary warm-gold outer curtain panels. Use invented dragon designs suited to this fictional dynasty. All prominent decorative motifs in this chamber use dragons or supporting cloud scrolls. In the foreground is a spacious reception area with warm hanging lanterns, a bronze incense burner and ivory stone flooring. Calm warm daylight, soft shading, fully made bed, austere stately ambiance, no people, no silhouettes, no lettering.
15. Consort Baek Hyeonbi's sickroom. Quiet, closely framed empty room with a neatly made bed, completely shut paper lattice windows, a small ceramic porcelain medicine bowl and covered decoction pot on a bedside table, subtle thread of medicinal steam. Warm ivory shaded light and restrained pale celadon linen with red-brown structural timber; subdued, private atmosphere.
16. Wide symmetrical view from the entrance inside the vast official imperial audience hall for court assemblies. A dragon throne is clearly visible at the far end on a very high broad dais reached by many stone steps. Vermilion pillars rise through the monumental space, with warm gold ornament, restrained dragon relief and soft daylight. On either side of the central aisle there are only broad, continuous expanses of bare ivory paving where court officials would stand during assemblies. Pale floor joints can softly suggest two ordered standing ranks. The gold dragon throne is the sole seat and the sole piece of furniture in the entire hall. Keep the entire lower hall from foreground to stairs physically and visibly clear, with zero chairs, stools, benches, tables, desks, individual stands, cushions, mats, dividers, or other objects along either flank. Show the imposing grand hall unoccupied, with no people, silhouettes or lettering.

p/16 카페트 편집 지시 (기존 대전 이미지 첨부)

> Edit the attached artwork of the fictional imperial audience hall. Make one precise local change to the foreground floor: add a single long woven palace carpet runner in muted warm vermilion red with a narrow antique-gold woven border and understated traditional cloud-scroll ornament. Align it exactly down the middle on the central aisle axis, running from the bottom foreground edge toward the golden dragon throne and ending on the floor just before the first stair. The carpet is distinctly narrower than the marked central aisle, with visible ivory floor margins and symmetrical perspective tapering. The steps stay bare. The broad floor spaces to the left and right stay empty for standing courtiers, with no chairs or furniture on the sides. Retain the fixed composition, angle, framing, architecture, gold dragon throne, stairs, columns, ornament, soft warm daylight, brown line art and cel shading from the image. No people, silhouettes, lettering, watermark, or extra furnishings. Match the existing 16:9 landscape aspect ratio and keep the camera in the same position.
>
> Edit this 16:9 artwork of the fictional imperial audience hall, preserving its exact symmetrical camera position, architecture, red columns, golden throne, soft cel shading and warm light. Make two specific changes. First, continue the existing red carpet runner with its narrow gold border up the CENTER of the entire high stone staircase to the upper landing directly in front of the golden throne. It must visibly follow the steps, showing the horizontal tread and vertical riser on every step and fitting the perspective, with broad bare stone stairs to its left and right; the carpet must never stop at the first stair. Second, remove every peony and all flower motifs from the entire hall, including the prominent central golden peony on the throne backrest, the two vertical wall panels beside it, the wide overhead beams, the ceiling panels and the rail reliefs. Replace these floral motifs everywhere with clear fictional Chinese imperial dragon motifs: identifiable serpentine horned dragons with clawed limbs, in muted gold where the existing ornament is gold, or carved stone where appropriate. Use matching miniature dragon borders where legible. Preserve the existing large gold dragons already on the columns and throne crest. Use dragon ornament throughout, with plain geometric trim as needed and no flowers or petal motifs whatsoever. Keep the standing space on each side of the central carpet empty and the dragon throne the only seat. No people, no lettering, no extra furniture. Keep all elements at the same visual scale and maintain 16:9 landscape.
>
> Make a precise local correction confined to the visible ceiling strip at the very top of this image. In the top central strip there are five small golden flower-shaped rosettes, each in a rectangular coffer between the joists. Replace every remaining rosette in those coffers with one clearly readable small gold coiled Chinese dragon, a small horizontal serpentine dragon with a recognizable head, long S-shaped body and pointed tail, in the same scale and old gold color. If a coffer is cropped by the top frame, continue the equivalent small dragon motif there as well. Replace any other remaining floral rosettes in the upper ceiling strip in the same way. No flower petals or flower-shaped emblems anywhere on the ceiling. Keep the framing, room, throne, stair carpet and every element below the top ceiling strip exactly as in the attached image. No lettering or people. 16:9 landscape, same art style.

</details>

- 2026-11-17: 이벤트 e/ 1차 — e/1,2,25,26,3,4,5,6,7,8,9,10 (1280×720). 첨부 규칙: 얼굴 나오는 인물 sheet만(2·25·26=bok, 3·4=soa, 6·7=baek, 나머지 없음). 교지 2→25·26은 e/2 구도 유지·품계 확장. 검수 `_work/check/6_e_1.webp`. PROMPTS.md 미수정.
- 2026-11-17: e/ 1차 수정 — e/2·25·26 교지 구도(주인공 왼쪽 아래 뒷모습·복 공공 오른쪽 계단, 바닥 거리), e/3 받침 없는 백자 찻잔, e/4 주인공 뒷모습+옻칠 함 행렬·구석 임소아. 이전 `_work/old/e_v1/`. 검수 `_work/check/6_e_1.webp` 갱신. PROMPTS.md 미수정.
- 2026-11-17: 이벤트 e/ 3차 — e/19,20,21,22,23,24 (1280×720). 첨부: 19=p/1+soyun, 20=p/14+soyun, 21=yukhan만(후궁전 뒤뜰 해질녘 글로), 22=p/13+yukhan, 23=p/6+sodam, 24=p/21+sodam. 배경 첫 첨부 Edit-first, 인물 시트 얼굴·머리·옷색 고정. 주인공 얼굴 없음(뒷모습·어깨·손·소매, 쪽빛 회청색). 중국풍만. 검수 `_work/check/6_e_3.webp`. PROMPTS.md 미수정.
- 2026-11-17: 상황 s/ 10장 — s/1–10 (1280×720). 기존 e/·p/를 색채·선 참고로 첨부(밝고 따뜻한 저대비). 첨부: 7만 bok_sheet(+e/2 스타일), 나머지 장면은 구도별 e/·p/ 색 참고. 주인공 얼굴 없음. 중국풍만. 검수 `_work/check/7_s.webp`. PROMPTS.md 미수정.

## 6단계 — s/ (10)

- [x] s/ — 만든 번호: 1–10 / 건너뜀: 없음. 검수 `_work/check/7_s.webp`

## 7단계 — e/ (18)

- [ ] e/ — 만든 번호: / 건너뜀:

## 8단계 — i/ (13)

- [x] i/ — 만든 번호: 1–13 / 건너뜀: 없음

- 2026-11-16 소품 i/1–i/13을 내장 이미지 생성 도구로 제작했다. 1장 비율표, 2장 그림체 블록, 10장 소품 표를 사용했다. 모든 소품은 옅은 아이보리 배경 한가운데에 화면 높이 절반 안팎으로 배치했다.
- `ref/ha_face.webp`와 각 소품을 비교해 갈색 선, 부드러운 셀 명암과 금빛 표현을 확인했다. i/10–i/12는 각 인물 시트도 첨부해 접부채의 은회색 구름무늬, 검집의 놋쇠 장식과 붉은 끈, 봉황 비녀의 금빛 날개와 진주 장식을 맞췄다.
- 장부는 한 권으로 읽히도록 다시 만들었고, 봉황 비녀와 약재 상자는 여백을 늘려 다시 만들었다. 교지와 서찰, 장부에는 글자가 없다. 찻잔, 향낭, 탕약 사발, 협죽도 꽃가지는 김·연기·경고 표시 없이 그렸다.
- 13장 모두 1280×720 WebP. `_work/check/5_items.webp`는 번호순 5열×3행. PROMPTS.md의 SHA-256은 작업 전과 일치한다. 소품 단계에서 종료.
- 2026-11-16 i/5와 i/7 첨부 편집. i/5는 주머니 입구를 열고 배 모양 중국 은정이 앞쪽으로 흘러나오게 수정했다. i/7은 둥근 밀랍 봉인을 없애고, 읽을 수 없는 추상 문양의 작은 사각 붉은 인장이 종이에 평면으로 찍힌 중국식 접지 서찰로 수정했다.
- 교체 전 원본은 `_work/old/i_5_before_money_ingots.webp`, `_work/old/i_7_before_square_seal.webp`에 보관했다. 수정본은 1280×720 WebP로 확인하고 `_work/check/5_items.webp`를 갱신했다. PROMPTS.md는 수정하지 않았다.
- 2026-11-16 i/5·i/7 재수정. i/5는 옆 구멍을 없애고 은정이 열린 입구에서만 나오게 했다. i/7은 세로 한지 봉투로 세우고, 빈 편지가 위쪽 입구로 조금 나오게 했다. 인장은 사각 구름 문양만 남겼다.
- 직전 파일은 `_work/old/i_5_before_intact_pouch.webp`, `_work/old/i_7_before_mulberry_envelope.webp`에 보관했다. 둘 다 1280×720 WebP. `_work/check/5_items.webp`를 갱신했다.

<details>
<summary>소품별 생성 프롬프트 구성</summary>

> The attached image is an art style reference only: match its line art, cel shading, color softness and gold rendering. Do not draw this woman or any person.

이어서 PROMPTS.md 2장의 그림체 블록 원문, 아래 구도 문장, 10장의 번호별 소품 설명 원문을 붙였다.

> a single prop illustration, centered, small in the frame, plain soft background, 16:9 landscape

> Fictional Chinese imperial palace prop, isolated as a 16:9 landscape romance-fantasy webtoon game asset. Show exactly one self-contained item. Entire silhouette is visible with abundant empty space. Place the object center at 50% of canvas width and height. Main object's top is around 26% of canvas height and bottom around 74% (object height 45–50% of the screen, excluding its subtle shadow). Keep the left and right halves mostly empty as well. Use a plain very pale warm ivory background and a single soft contact shadow below the item. One unified color field, no horizon line, setting, room, border, or graphic backdrop. Match reference's delicate warm brown ink contours, 3–4 soft cel shade values, muted palette, and restrained amber-gold highlights only on gold surfaces. The person-specific instructions in the style block apply only to how the artwork is rendered. Do not draw any human, hands, silhouettes, characters or writing. No logos or watermark.

1. One handleless, footed white porcelain teacup, shown at a soft three-quarter angle with the inside rim visible, undecorated ivory glaze and light warm grey underpainting. A still surface of ordinary clear pale tea may be visible. The cup is the only object, without saucer or spoon. No vapour, fumes, smoke, symbols or spotlights.
2. One delicate traditional silver hairpin, fine long silver shaft and a small softly chiselled plum blossom finial, subdued silver values with clean ink strokes. Angle it diagonally from lower left to upper right so the silhouette is about half the frame height. No other jewellery or gold.
3. One ordinary sewn silk scent sachet, muted warm sage or dusty mauve, slightly rounded flatter fabric pouch with a simple cord and short integrated tassel. A restrained botanical embroidery motif. Closed, without loose material, smoke, vapour, warning markings or mysterious glow.
4. One modest plain warm off-white glazed ceramic bowl, low foot and softly cel-shaded rim. Viewed slightly from above with a quiet flat surface of dark warm brown herbal drink. No separate objects, solid ingredients, garnish, steam, smoke, symbols, bubbles or glow.
5. One small muted blue-green silk coin pouch, softly creased and gathered by a beige knotted drawstring, slightly plump and entirely closed. Visual weight suggests coins inside. No scattered coins, letters or multiple bags.
6. One imperial decree handscroll, visibly partly unrolled to reveal pristine blank warm ivory paper across the whole interior. Two dowels are integrated into the same scroll, with small restrained antique-gold caps and a slim muted imperial ochre brocade border. Angle it slightly in perspective. No script, seals, embossing or ink of any kind.
7. One sealed period-appropriate folded letter made of warm cream paper with a small plain red seal fastening the overlap. Use a simple folded-paper packet rather than a modern postal envelope. The visible paper and seal are completely blank; no stamp, signature, letters, ideographs or crown.
8. A single traditional thread-bound palace account ledger lies closed at the center. A visibly unified small book with a plain soft dark slate-indigo cloth cover, short visible parallel cream page edges and three subtle thread stitches along a single spine. No duplicate book, no loose paper, no pages spread open, no ornate border, no lettering anywhere. Tiny in the frame with generous plain ivory above and below. A single delicate contact shadow, muted warm values and brown linework.
9. One cut oleander flowering twig as a neutral botanical illustration, narrow lance-shaped green leaves along the stem and a cluster of pink five-petaled flowers. A diagonal placement, soft cel shading and a delicate shadow. No vase, other props, droplets, smoke, effects, stains or danger marks.
10. Image 2 is the precise object design reference. Isolate the Prince's folding fan visible in the central close-up on image 2. Preserve the same partly opened fan arc, pale ivory pleated leaf with several pale silver-grey curling cloud motifs, slim dark brown wooden ribs fanning out from the simple pivot and brown outer guard. Cleanly reconstruct the tiny part that is covered by his hand. The fan alone, slightly diagonal, no person or hand, no jade tassel or other embellishments.
11. Image 2 is the precise design reference for the existing palace guard's sword. Show the single sword fully sheathed, with the same slim straight dark brown scabbard, muted brass-coloured throat bands and chape, and unobtrusive rounded brass pommel that are visible on his two full-body views. Add the thin winding red cord specified for this prop, wrapped neatly near the top of the scabbard and grip, reading as a restrained dark brick red accent. Place the entire weapon on a moderate diagonal, pommel up to the left and sheathed tip down to the right, occupying about half the image height. No exposed blade, hands, body, action or extra objects.
12. Image 2 is the precise object design reference. Isolate the empress's gold phoenix hairpin and preserve the position of its head, raised wings, curling floral filigree and the pearl swags and teardrops. All chains and beads are part of the ornament; cleanly exclude her head, hair and earrings. Frame significantly farther back as a wide shot. All the ornament's visible gold and pearls together occupy no more than the central 49 percent of the image height, from y=26% to y=74%, and about 39% of the image width, with the entire top quarter and bottom quarter totally empty. Render it by itself on the same warm ivory background with a nearly imperceptible soft contact shadow. Same visual scale as a small object in a game background.
13. One small traditional apothecary chest made of muted red-brown wood with its hinged lid partly open, softly revealing a few plain cream packets arranged inside fixed fitted compartments. Subtle gold or brass hardware. Use a very distant wide still-life composition, with the entire chest and open lid together from y=26% to y=74% of frame, about 48% of height, and ample negative space in all directions. One pale ivory seamless color field and a single faint shadow. No lettering or loose items outside the chest.

</details>

## 확정 (2026-11-12 최종)

- 장소 p/1~p/29: 작가 확정 (2026-11-16). 고치지 않는다.

- 그림체·선: 시험 1번 + 「반반」, 채도 보정 없음, 종이 질감 없음
- 여자 복식: 명나라풍 세운 깃 (ha_mid 기준)
- ha_face = 하 귀비 전신 최종 (12:04, 그림체·복식·비율 기준 그림)

## 확정한 시트

- soyun, sodam, yukhan, dan, wi (작가 확정 2026-11-03 오후 최종). ha는 확정 취소, 다시 만든다. 다시 만들지 않는다. **다른 인물을 만들 때 첨부하지 않는다** (PROMPTS.md 4장, 11-03 다시 정함).

## 얼굴 먼저 (11-03 새 순서, 9명)

- [x] ha_face — v2 생성 완료 / 얼굴 확인 대기 (작가 미확정):
- [x] on_face — v2 생성 완료 / 얼굴 확인 대기 (작가 미확정):
- [x] jeong_face — v2 생성 완료 / 얼굴 확인 대기 (작가 미확정):
- [x] baek_face — v2 생성 완료 / 얼굴 확인 대기 (작가 미확정):
- [x] sohwa_face — v2 생성 완료 / 얼굴 확인 대기 (작가 미확정):
- [x] soa_face — v2 생성 완료 / 얼굴 확인 대기 (작가 미확정):
- [x] heo_face — v2 생성 완료 / 얼굴 확인 대기 (작가 미확정):
- [x] bok_face — v2 생성 완료 / 얼굴 확인 대기 (작가 미확정):
- [x] yeona_face — v2 생성 완료 / 얼굴 확인 대기 (작가 미확정):

## 다시 만들 것

- sodam, dan 시트: soyun과 얼굴·자세·머리 장식이 너무 비슷해서 PROMPTS.md 4장 새 규칙으로 다시 만든다 (2026-11-02)

- on(온 숙비), baek(백 현비): 후궁인데 옷차림이 초라하고 현비가 귀신처럼 나옴. 4장 새 행으로 다시 만든다 (2026-11-03)
- jeong(정 덕비): 너무 나이 들게 나옴. 귀비와 비슷한 나이로 다시 만든다 (2026-11-03)
- sohwa(장공주), yeona(연아): 너무 어리게 나옴. 주인공 23세 기준으로 소화 24세, 연아 22세로 다시 만든다 (2026-11-03)
- soa(임소아): 너무 어리게 나옴. 22세 성인으로 다시 만든다 (2026-11-03)
- 여자 인물 얼굴이 모두 비슷함: 얼굴 라인업을 먼저 만들고 시트를 다시 만든다

## 질문 (지시서가 애매하거나 틀린 곳)

- GPT 참고 시트에 짙은 녹색 젊은 남자가 있다. 정 덕비 행은 40대 여성이라 그 칸은 붙이지 않고 프롬프트로 만들었다.
- 단은 참고 시트와 같이 흰 기 많은 보라 옷이지만, 행에 적힌 50대 주름보다 젊어 보인다.

## 메모

- 하 귀비 옷 교체, 작가 확인 대기
- 하 귀비 기준 그림을 당나라풍 복식으로 교체. 직전 교차 깃 버전은 `_work/old/face_v3/ha_face_cross_collar.webp`에 보관.
- 기준 그림 완료, 작가 확인 대기
- 하 귀비 그림체 기준으로 8명(백·온·소아·연아·단·위·허·육한) 보정. 기존 얼굴과 하 귀비를 순서대로 첨부. 육한의 갑옷·옷은 짙은 쪽빛.
- 정덕비는 하 귀비를 그림체 참고로 첨부해 큰 검은 눈과 점 없는 얼굴로 제작. 복 공공은 작가가 지정한 구본의 둥근 볼과 눈웃음·자세를 참고하고 하 귀비 그림체로 40대 후반~50세 중년 남성을 다시 그림. 기존 파일 10장은 `_work/old/face_v2/`에 보관. 새 결과를 하 귀비와 대조하고 14장 확인판 갱신. **얼굴 확인 대기.**
- 소담 얼굴 재수정. 같은 참고 세 장을 사용해 소윤과 닮은 곧은 콧대와 갸름한 얼굴형, 더 부드러운 턱선, 눈꼬리가 살짝 올라간 옅은 금빛 아몬드형 눈으로 변경. 입을 다문 무표정과 은발·옥색 옷·옥 장식 유지. 얼굴 확인판 갱신.
- 소담 재생성. 소담 원본(은발·옥색 옷·옥 장식), 하(그림체), 소윤(이복형의 얼굴형·콧대·턱선)을 이 순서로 첨부. 조금 더 크게 뜬 부드러운 옅은 금빛 눈, 얇은 눈썹, 다문 입, 웃음과 보조개 없는 표정으로 수정. 얼굴 확인판 갱신.
- 소화는 기존 얼굴 한 장으로 반묶음 머리만 편집. 원본은 `_work/old/face_v2/sohwa_face.webp`에 보관. 소담은 기존 얼굴을 바탕으로 1번 그림체에 맞추고, 부드러운 눈빛에 입을 다문 무표정으로 수정. 얼굴 확인판 갱신.
- 2026-11-12 그림체 1번(한국 로판 웹툰 표지풍) 확정. 기존 ref/ 파일 15개를 `_work/old/style_v1/`에 보관.
- 얼굴 14장 및 `_work/faces_check.webp`(4×4) 저장. ha는 작가 확정 시험본 복사, soyun은 본인 구 시트 한 장을 사용해 다시 그림. 나머지 12명은 첨부 없이 생성. **얼굴 확인 대기.**
- 그림체 시험 8장 완료
- 태후 단씨 얼굴 재생성. 40대 초반의 마른 체형, 높은 광대와 갸름한 얼굴, 검은 머리의 은빛 한 줄, 가지색 학 문양 교차깃. 첨부 없음.

### ha 실제 얼굴 생성 프롬프트

```text
The attached images show clothing only. Use them only as a reference for line art, coloring, shading and rendering quality. Do not copy any face. modern Korean romance-fantasy webtoon cover art, 2020s quality, semi-realistic anime proportions, clean refined digital line art with crisp fine ink lines, long flowing hair with loose wispy strands, pale luminous skin, polished cel shading blended with soft gradients and gentle glossy highlights, muted desaturated palette with one clear accent color per character, elegant silk robes with restrained embroidery, only the ornaments written in the character description, not old-fashioned, not dated 2000s anime, not overly ornate, no dense busy patterns, not cluttered, not photorealistic, not chibi. Delicate thin, subtly textured dark ink contours support restrained cel-shaded shadow planes softened by light gradients, with small controlled satin highlights rather than a wet gloss, smoothly painted luminous ivory skin with muted warm blush, layered translucent iris colors and tiny catchlights framed by individually inked lashes, flowing hair built from fine tapered strands and broad subdued sheen bands, and weighty silk folds with finely drawn metallic-thread embroidery, all in a softly lit, moderately bright, desaturated palette with deep but gentle shadows. head-and-shoulders portrait facing the viewer straight on, plain white background, 1:1 square, 1024x1024. modest fully closed collar, no cleavage, no emphasis on chest, no text, no watermark. Fictional Chinese-style clothing, no Joseon clothing. Single person only. heart-shaped face with high cheekbones, medium almond-shaped amber eyes with long winged red eyeliner and a heavy-lidded haughty gaze, sharp arched eyebrows, straight refined nose, full red lips, a beauty mark under one eye. woman in her late 20s, haughty smirk, dark brown hair piled very high with many gold flower ornaments and dangling gold chains, rich gold and apricot robe. Main color gold.Only gold FLOWER HAIR ornaments and hanging HAIR chains. Bare ears, no earrings. Keep the entire hairstyle inside the square with a little white margin.
```

### on 실제 얼굴 생성 프롬프트

```text
The attached images show clothing only. Use them only as a reference for line art, coloring, shading and rendering quality. Do not copy any face. modern Korean romance-fantasy webtoon cover art, 2020s quality, semi-realistic anime proportions, clean refined digital line art with crisp fine ink lines, long flowing hair with loose wispy strands, pale luminous skin, polished cel shading blended with soft gradients and gentle glossy highlights, muted desaturated palette with one clear accent color per character, elegant silk robes with restrained embroidery, only the ornaments written in the character description, not old-fashioned, not dated 2000s anime, not overly ornate, no dense busy patterns, not cluttered, not photorealistic, not chibi. Delicate thin, subtly textured dark ink contours support restrained cel-shaded shadow planes softened by light gradients, with small controlled satin highlights rather than a wet gloss, smoothly painted luminous ivory skin with muted warm blush, layered translucent iris colors and tiny catchlights framed by individually inked lashes, flowing hair built from fine tapered strands and broad subdued sheen bands, and weighty silk folds with finely drawn metallic-thread embroidery, all in a softly lit, moderately bright, desaturated palette with deep but gentle shadows. head-and-shoulders portrait facing the viewer straight on, plain white background, 1:1 square, 1024x1024. modest fully closed collar, no cleavage, no emphasis on chest, no text, no watermark. Fictional Chinese-style clothing, no Joseon clothing. Single person only. long oval face, medium-size narrow grey-brown eyes with drooping outer corners, always looking slightly down, faint thin eyebrows, small nose, thin lips. woman in her late 20s, expression calm and reserved. light brown hair in an elegant consort's updo with silver hairpins and small jade flowers, layered grey-green silk consort robe with fine silver embroidery and a pale inner layer, refined earrings — understated but clearly a high-ranking imperial consort, not plain, not poor. Main color grey-green. Full hairstyle inside frame.
```

### baek 실제 얼굴 생성 프롬프트

```text
The attached images show clothing only. Use them only as a reference for line art, coloring, shading and rendering quality. Do not copy any face. modern Korean romance-fantasy webtoon cover art, 2020s quality, semi-realistic anime proportions, clean refined digital line art with crisp fine ink lines, long flowing hair with loose wispy strands, pale luminous skin, polished cel shading blended with soft gradients and gentle glossy highlights, muted desaturated palette with one clear accent color per character, elegant silk robes with restrained embroidery, only the ornaments written in the character description, not old-fashioned, not dated 2000s anime, not overly ornate, no dense busy patterns, not cluttered, not photorealistic, not chibi. Delicate thin, subtly textured dark ink contours support restrained cel-shaded shadow planes softened by light gradients, with small controlled satin highlights rather than a wet gloss, smoothly painted luminous ivory skin with muted warm blush, layered translucent iris colors and tiny catchlights framed by individually inked lashes, flowing hair built from fine tapered strands and broad subdued sheen bands, and weighty silk folds with finely drawn metallic-thread embroidery, all in a softly lit, moderately bright, desaturated palette with deep but gentle shadows. head-and-shoulders portrait facing the viewer straight on, plain white background, 1:1 square, 1024x1024. modest fully closed collar, no cleavage, no emphasis on chest, no text, no watermark. Fictional Chinese-style clothing, no Joseon clothing. Single person only. slender inverted-triangle face, large light grey eyes with deep double eyelids, thin arched eyebrows, small sharp nose, very pale almost colorless lips, pale skin. woman about 30, porcelain skin with faint unwell pallor, slightly bluish pallor around eyes and lips, faintly flushed tired eyelids, expression composed with a faint weary smile. black hair neatly arranged in a consort's updo with pearl and silver ornaments, layered white and pale silver silk consort robe with fine embroidery and a light shawl — elegant imperial consort who is ill, not a ghost, not disheveled, no dark circles, no hollow cheeks. Main color white and silver. No earrings. Clearly large open eyes with visible deep eyelid folds, delicately tapering narrow chin. Full hairstyle inside frame.
```

### sohwa 실제 얼굴 생성 프롬프트

```text
The attached images show clothing only. Use them only as a reference for line art, coloring, shading and rendering quality. Do not copy any face. modern Korean romance-fantasy webtoon cover art, 2020s quality, semi-realistic anime proportions, clean refined digital line art with crisp fine ink lines, long flowing hair with loose wispy strands, pale luminous skin, polished cel shading blended with soft gradients and gentle glossy highlights, muted desaturated palette with one clear accent color per character, elegant silk robes with restrained embroidery, only the ornaments written in the character description, not old-fashioned, not dated 2000s anime, not overly ornate, no dense busy patterns, not cluttered, not photorealistic, not chibi. Delicate thin, subtly textured dark ink contours support restrained cel-shaded shadow planes softened by light gradients, with small controlled satin highlights rather than a wet gloss, smoothly painted luminous ivory skin with muted warm blush, layered translucent iris colors and tiny catchlights framed by individually inked lashes, flowing hair built from fine tapered strands and broad subdued sheen bands, and weighty silk folds with finely drawn metallic-thread embroidery, all in a softly lit, moderately bright, desaturated palette with deep but gentle shadows. head-and-shoulders portrait facing the viewer straight on, plain white background, 1:1 square, 1024x1024. modest fully closed collar, no cleavage, no emphasis on chest, no text, no watermark. Fictional Chinese-style clothing, no Joseon clothing. Single person only. oval face with slightly high cheekbones, large upturned cat-like gold eyes, bold angled eyebrows, small nose, full lips, one-sided smirk. woman of 24, grown adult not teenager, one eyebrow raised, black hair with a reddish tint in an elegant princess updo with gold ornaments and small gold bells, vermilion silk robe with gold trim, jeweled earrings. Main color vermilion. Broad adult oval facial outline rather than pointed heart chin, noticeably wide-open upward-tilted gold eyes and a crooked playful smirk. Full hairstyle inside frame.
```


### 확정 시트 그림체 문장

Delicate thin, subtly textured dark ink contours support restrained cel-shaded shadow planes softened by light gradients, with small controlled satin highlights rather than a wet gloss, smoothly painted luminous ivory skin with muted warm blush, layered translucent iris colors and tiny catchlights framed by individually inked lashes, flowing hair built from fine tapered strands and broad subdued sheen bands, and weighty silk folds with finely drawn metallic-thread embroidery, all in a softly lit, moderately bright, desaturated palette with deep but gentle shadows.

- 확정 시트 다섯 장을 직접 열어 확인. wi 왼쪽 전신 (80,265)–(410,620), soyun 왼쪽 전신 (65,180)–(435,610)을 잘라 `_work/style_ref_1.webp`, `_work/style_ref_2.webp` 저장. 얼굴·턱·입 제외.
- 추가 지시에 따라 얼굴 생성에는 위 옷 부분 두 장만 첨부. 앞서 생성한 ha/on은 채택하지 않고 새 기준으로 재생성.

soyun 시트는 작가가 고른 GPT 그림으로 교체했다. `ref/soyun_sheet.webp`는 그 파일을 1500×1000 webp로 맞춘 것이다. 아래 프롬프트는 교체 전에 만든 시트용이라, 지금 파일과는 다르다.

soyun 시트 머리색 흑발로 수정 (v2). 작가 확정. `ref/soyun_sheet.webp`를 v2로 덮어씀.

소윤을 뺀 13장은 작가가 준 GPT 시트를 참고하고, 4장 인물 행으로 다시 만들었다. 눈매 문장은 뺐다. soyun 시트는 첨부하지 않았다. 녹색 젊은 남자 칸은 정 덕비에 쓰지 않았다.

sodam 시트 레이아웃과 머리 모양 수정 (v2). 전신 비율을 soyun 시트에 맞춰 v2를 다시 저장함. 원래 `ref/sodam_sheet.webp`는 그대로.

2026-11-03: PROMPTS 2·4장 개정. dan·wi·ha 첨부 규칙 폐기. on·jeong·baek·sohwa·soa·yeona는 `_face.webp` 6장 생성(첨부 없음). 해당 `_sheet.webp`는 `_work/old/`로 이동. 시트는 작가 얼굴 확정 후.

얼굴 재작업: 남성 시트(soyun·sodam·yukhan)를 색·선 참고에 쓰면 여성이 남자로 나옴 → **여성 확정 시트(dan·wi·ha)만** 선·색 참고. on·sohwa·yeona 작가 확정. jeong·baek·soa는 재생성본 확인 대기.

```
semi-realistic anime webtoon illustration, crisp fine ink linework, long flowing hair with many loose wispy strands drifting in the air, sharp elegant narrow eyes with defined eyeliner and lashes, half-lidded calm gaze, subtle faint smile, pale luminous skin, cel shading blended with soft gradients and gentle glossy highlights, muted desaturated palette with one clear accent color per character, intricately embroidered silk robes with fine gold or silver thread, delicate earrings and hairpins, not photorealistic, not chibi (except gag faces), character reference sheet, pure flat white background, three panels side by side: full body front view on the left, head-and-shoulders close-up in the center, exact side profile full body on the right, figures fill about 90% of the frame height, small margins, feet and hair ornaments fully inside the frame, all three panels evenly spaced, nothing cut off at any edge, neutral expression, same outfit in all views, no text, no letters, no labels, no title, no watermark, no captions, young emperor of a fictional Chinese-style empire, man in his late 20s, tall and lean, bored languid half-lidded eyes, dark gold eyes, black hair half tied up under a small gold crown, black imperial robe with gold thread dragon-cloud patterns (fictional design), wide sleeves, jade belt. Main colors black and gold, modest fully closed collar
```

## 2026-11-03 이번 작업

- [x] 정리: 소담 구본을 `_work/old/sodam_sheet_old.webp`로 이동, v2를 `ref/sodam_sheet.webp`로 이름 변경. ha·heo·bok 시트와 ref의 기존 얼굴 전부 `_work/old/`로 이동.
- 확정본 보존 SHA256: {'soyun': 'a54b7eccdf0cf987d58017e02abcc6eb50ebd4b0cc3e614de03348332d41ff3e', 'yukhan': '3dd8695cef58eabecae1d2ed380be079019575690af430513e09d04ab9d66923', 'dan': 'de7687f603b88be9020c3aa52d09b7dd0bab6b5c17508e48817b309d83d6c51e', 'wi': '6eb76d8769cc9a134ab225ad0f928470f6c851bba36bf6edd997daacf0c36e4b', 'sodam': '0c89673f931aa9fa52e924f9d4ed32d67c88ea5583f9277de0b397aa431553ce'}
- 얼굴 9장: 내장 image_gen 사용, 다른 인물·참고 이미지 첨부 없이 각각 독립 생성. 시트는 만들지 않음.

- 작가 추가 지시: 정덕비는 다른 후궁과 같은 수준의 고운 미모로 재생성. 작은 홑꺼풀·일자 눈썹·턱 점 유지. 옷 대표색은 짙은 녹색 대신 **하늘색 계열**로 변경 (이번 대화 지시 우선, PROMPTS.md 수정 없음).

## 얼굴 v2 — 수정 그림체 적용

### 얼굴 v2 최종 프롬프트 — 내장 image_gen

#### ha

```text
The attached images show clothing only. Use them only as a reference for line art, coloring, shading and rendering quality. Do not copy any face. Korean webtoon character illustration, warm ivory paper-like overall tone,
clean dark-brown ink outlines of medium weight, slightly thicker contour lines around the face and body,
soft flat cel shading with gentle warm shadows (not painterly, not glossy 3D rendering),
warm peach-beige skin with a soft natural blush, light natural makeup,
eyes drawn with clear dark upper lash lines, warm-toned irises with one small highlight,
long hair drawn with many fine individual line strands and a few loose wisps,
muted warm palette with one clear accent color per character,
silk robes with readable embroidery, only the ornaments written in the character description,
three-quarter view, beautiful delicate attractive faces (every young character must look pretty or handsome),
not glossy, not hyper-detailed Chinese game CG, not cool blue-white skin, not heavy dramatic makeup,
not old-fashioned, not overly ornate, no dense busy patterns, not photorealistic, not chibi.
head-and-shoulders portrait, three-quarter view, plain white background, 1:1 square, 1024x1024.
modest fully closed collar, no cleavage, no emphasis on chest. no text, no watermark. Fictional Chinese-style clothing, no Joseon clothing. Entire hairstyle inside frame. Hand-drawn 2D illustration with clearly visible brown contour ink, matte untextured skin color fills, simple two-tone cel shadow shapes, no airbrushed face modeling, no skin specular shine. heart-shaped face with high cheekbones, medium almond-shaped amber eyes with fine long winged red eyeliner and a heavy-lidded haughty gaze, sharp arched eyebrows, straight refined nose, full red lips, a beauty mark under one eye. woman in her late 20s, haughty smirk, dark brown hair piled very high with many gold flower ornaments and dangling gold chains, rich gold and apricot robe. Main color gold.Only gold FLOWER HAIR ornaments and hanging HAIR chains. Bare ears, no earrings. Keep the entire hairstyle inside the square with a little white margin. Keep red makeup accents fine and restrained, not smoky or thick.
```

#### on

```text
The attached images show clothing only. Use them only as a reference for line art, coloring, shading and rendering quality. Do not copy any face. Korean webtoon character illustration, warm ivory paper-like overall tone,
clean dark-brown ink outlines of medium weight, slightly thicker contour lines around the face and body,
soft flat cel shading with gentle warm shadows (not painterly, not glossy 3D rendering),
warm peach-beige skin with a soft natural blush, light natural makeup,
eyes drawn with clear dark upper lash lines, warm-toned irises with one small highlight,
long hair drawn with many fine individual line strands and a few loose wisps,
muted warm palette with one clear accent color per character,
silk robes with readable embroidery, only the ornaments written in the character description,
three-quarter view, beautiful delicate attractive faces (every young character must look pretty or handsome),
not glossy, not hyper-detailed Chinese game CG, not cool blue-white skin, not heavy dramatic makeup,
not old-fashioned, not overly ornate, no dense busy patterns, not photorealistic, not chibi.
head-and-shoulders portrait, three-quarter view, plain white background, 1:1 square, 1024x1024.
modest fully closed collar, no cleavage, no emphasis on chest. no text, no watermark. Fictional Chinese-style clothing, no Joseon clothing. Entire hairstyle inside frame. Hand-drawn 2D illustration with clearly visible brown contour ink, matte untextured skin color fills, simple two-tone cel shadow shapes, no airbrushed face modeling, no skin specular shine. long oval face, medium-size narrow grey-brown eyes with drooping outer corners, always looking slightly down, faint thin eyebrows, small nose, thin lips. woman in her late 20s, expression calm and reserved. light brown hair in an elegant consort's updo with silver hairpins and small jade flowers, layered grey-green silk consort robe with fine silver embroidery and a pale inner layer, refined earrings — understated but clearly a high-ranking imperial consort, not plain, not poor. Main color grey-green. Full hairstyle inside frame.
```

#### jeong

```text
The attached images show clothing only. Use them only as a reference for line art, coloring, shading and rendering quality. Do not copy any face. Korean webtoon character illustration, warm ivory paper-like overall tone,
clean dark-brown ink outlines of medium weight, slightly thicker contour lines around the face and body,
soft flat cel shading with gentle warm shadows (not painterly, not glossy 3D rendering),
warm peach-beige skin with a soft natural blush, light natural makeup,
eyes drawn with clear dark upper lash lines, warm-toned irises with one small highlight,
long hair drawn with many fine individual line strands and a few loose wisps,
muted warm palette with one clear accent color per character,
silk robes with readable embroidery, only the ornaments written in the character description,
three-quarter view, beautiful delicate attractive faces (every young character must look pretty or handsome),
not glossy, not hyper-detailed Chinese game CG, not cool blue-white skin, not heavy dramatic makeup,
not old-fashioned, not overly ornate, no dense busy patterns, not photorealistic, not chibi.
head-and-shoulders portrait, three-quarter view, plain white background, 1:1 square, 1024x1024.
modest fully closed collar, no cleavage, no emphasis on chest. no text, no watermark. Fictional Chinese-style clothing, no Joseon clothing. Entire hairstyle inside frame. Hand-drawn 2D illustration with clearly visible brown contour ink, matte untextured skin color fills, simple two-tone cel shadow shapes, no airbrushed face modeling, no skin specular shine. long face with a defined jawline, small narrow single-lidded black eyes, thick straight eyebrows, high nose bridge, medium lips, a small mole on the chin. woman in her late 20s, youthful beautiful delicate feminine imperial consort, harmonious refined proportions, peaceful faint smile. black hair in a neat elegant consort's updo with jade hairpins, sky-blue silk consort robe with gold-thread embroidery. Main color muted sky blue. No earrings, no crown, no grey hair. Keep her small monolid eyes graceful, thick straight brows finely inked rather than blocky. Softly defined jaw, not masculine or harsh.
```

#### baek

```text
The attached images show clothing only. Use them only as a reference for line art, coloring, shading and rendering quality. Do not copy any face. Korean webtoon character illustration, warm ivory paper-like overall tone,
clean dark-brown ink outlines of medium weight, slightly thicker contour lines around the face and body,
soft flat cel shading with gentle warm shadows (not painterly, not glossy 3D rendering),
warm peach-beige skin with a soft natural blush, light natural makeup,
eyes drawn with clear dark upper lash lines, warm-toned irises with one small highlight,
long hair drawn with many fine individual line strands and a few loose wisps,
muted warm palette with one clear accent color per character,
silk robes with readable embroidery, only the ornaments written in the character description,
three-quarter view, beautiful delicate attractive faces (every young character must look pretty or handsome),
not glossy, not hyper-detailed Chinese game CG, not cool blue-white skin, not heavy dramatic makeup,
not old-fashioned, not overly ornate, no dense busy patterns, not photorealistic, not chibi.
head-and-shoulders portrait, three-quarter view, plain white background, 1:1 square, 1024x1024.
modest fully closed collar, no cleavage, no emphasis on chest. no text, no watermark. Fictional Chinese-style clothing, no Joseon clothing. Entire hairstyle inside frame. Hand-drawn 2D illustration with clearly visible brown contour ink, matte untextured skin color fills, simple two-tone cel shadow shapes, no airbrushed face modeling, no skin specular shine. slender inverted-triangle face, large light grey eyes with deep double eyelids, thin arched eyebrows, small sharp nose, very pale almost colorless lips, pale skin. woman about 30, delicate beautiful imperial consort, slight unwell pallor but warm ivory skin undertone, faint weary smile, no dark circles, no hollow cheeks, not a ghost. black hair neatly arranged in a consort's updo with pearl and silver ornaments, layered white and pale silver silk consort robe with fine embroidery and a light shawl. Main color white and silver. No earrings. Large open double-lidded eyes, narrow tapering chin.
```

#### sohwa

```text
The attached images show clothing only. Use them only as a reference for line art, coloring, shading and rendering quality. Do not copy any face. Korean webtoon character illustration, warm ivory paper-like overall tone,
clean dark-brown ink outlines of medium weight, slightly thicker contour lines around the face and body,
soft flat cel shading with gentle warm shadows (not painterly, not glossy 3D rendering),
warm peach-beige skin with a soft natural blush, light natural makeup,
eyes drawn with clear dark upper lash lines, warm-toned irises with one small highlight,
long hair drawn with many fine individual line strands and a few loose wisps,
muted warm palette with one clear accent color per character,
silk robes with readable embroidery, only the ornaments written in the character description,
three-quarter view, beautiful delicate attractive faces (every young character must look pretty or handsome),
not glossy, not hyper-detailed Chinese game CG, not cool blue-white skin, not heavy dramatic makeup,
not old-fashioned, not overly ornate, no dense busy patterns, not photorealistic, not chibi.
head-and-shoulders portrait, three-quarter view, plain white background, 1:1 square, 1024x1024.
modest fully closed collar, no cleavage, no emphasis on chest. no text, no watermark. Fictional Chinese-style clothing, no Joseon clothing. Entire hairstyle inside frame. Hand-drawn 2D illustration with clearly visible brown contour ink, matte untextured skin color fills, simple two-tone cel shadow shapes, no airbrushed face modeling, no skin specular shine. oval face with slightly high cheekbones, large upturned cat-like gold eyes, bold angled eyebrows, small nose, full lips, one-sided smirk. woman of 24, grown adult not child or teenager, lively beautiful feminine face, one eyebrow raised. black hair with a reddish tint in an elegant princess updo with gold ornaments and small gold bells, vermilion silk robe with gold trim, jeweled earrings. Main color vermilion. Clearly large wide-open upturned cat eyes, fuller oval cheeks, playful lopsided smile. No red eyeliner, no dramatic makeup.
```

#### soa

```text
The attached images show clothing only. Use them only as a reference for line art, coloring, shading and rendering quality. Do not copy any face. Korean webtoon character illustration, warm ivory paper-like overall tone,
clean dark-brown ink outlines of medium weight, slightly thicker contour lines around the face and body,
soft flat cel shading with gentle warm shadows (not painterly, not glossy 3D rendering),
warm peach-beige skin with a soft natural blush, light natural makeup,
eyes drawn with clear dark upper lash lines, warm-toned irises with one small highlight,
long hair drawn with many fine individual line strands and a few loose wisps,
muted warm palette with one clear accent color per character,
silk robes with readable embroidery, only the ornaments written in the character description,
three-quarter view, beautiful delicate attractive faces (every young character must look pretty or handsome),
not glossy, not hyper-detailed Chinese game CG, not cool blue-white skin, not heavy dramatic makeup,
not old-fashioned, not overly ornate, no dense busy patterns, not photorealistic, not chibi.
head-and-shoulders portrait, three-quarter view, plain white background, 1:1 square, 1024x1024.
modest fully closed collar, no cleavage, no emphasis on chest. no text, no watermark. Fictional Chinese-style clothing, no Joseon clothing. Entire hairstyle inside frame. Hand-drawn 2D illustration with clearly visible brown contour ink, matte untextured skin color fills, simple two-tone cel shadow shapes, no airbrushed face modeling, no skin specular shine. round face with soft full cheeks, large round doe-like brown eyes, soft rounded eyebrows, rounded nose tip, small lips, a dimple when smiling. woman of 22, a grown adult not child not teenager, adult facial proportions, light rosy cheeks, expression sweet friendly smile. brown hair in an elegant low-rank consort's updo with small pink flowers and a simple silver hairpin (no childish braids, no crown), pale pink silk robe with light embroidery — modest lowest rank but clearly a palace consort. Main color pale pink. No earrings. Clearly rounded jaw, full cheek contours and round eyes. Full hairstyle inside frame.
```

#### heo

```text
The attached images show clothing only. Use them only as a reference for line art, coloring, shading and rendering quality. Do not copy any face. Korean webtoon character illustration, warm ivory paper-like overall tone,
clean dark-brown ink outlines of medium weight, slightly thicker contour lines around the face and body,
soft flat cel shading with gentle warm shadows (not painterly, not glossy 3D rendering),
warm peach-beige skin with a soft natural blush, light natural makeup,
eyes drawn with clear dark upper lash lines, warm-toned irises with one small highlight,
long hair drawn with many fine individual line strands and a few loose wisps,
muted warm palette with one clear accent color per character,
silk robes with readable embroidery, only the ornaments written in the character description,
three-quarter view, beautiful delicate attractive faces (every young character must look pretty or handsome),
not glossy, not hyper-detailed Chinese game CG, not cool blue-white skin, not heavy dramatic makeup,
not old-fashioned, not overly ornate, no dense busy patterns, not photorealistic, not chibi.
head-and-shoulders portrait, three-quarter view, plain white background, 1:1 square, 1024x1024.
modest fully closed collar, no cleavage, no emphasis on chest. no text, no watermark. Fictional Chinese-style clothing, no Joseon clothing. Entire hairstyle inside frame. Hand-drawn 2D illustration with clearly visible brown contour ink, matte untextured skin color fills, simple two-tone cel shadow shapes, no airbrushed face modeling, no skin specular shine. man in his early 50s (not elderly, no white beard), long thin face with sunken cheeks, small nervous eyes with fine wrinkles, faint drooping eyebrows, long nose, thin moustache and a short goatee, anxious timid look. half-grey hair in a topknot under a black physician's cap, deep navy physician's robe. Main color deep navy. No jewelry, no crown, no earrings. Subtle middle-aged skin rendering, no elderly sagging or heavy age spots. Entire cap inside frame. No decorative gold embroidery on physician robe; plain practical deep navy fabric.
```

#### bok

```text
The attached images show clothing only. Use them only as a reference for line art, coloring, shading and rendering quality. Do not copy any face. Korean webtoon character illustration, warm ivory paper-like overall tone,
clean dark-brown ink outlines of medium weight, slightly thicker contour lines around the face and body,
soft flat cel shading with gentle warm shadows (not painterly, not glossy 3D rendering),
warm peach-beige skin with a soft natural blush, light natural makeup,
eyes drawn with clear dark upper lash lines, warm-toned irises with one small highlight,
long hair drawn with many fine individual line strands and a few loose wisps,
muted warm palette with one clear accent color per character,
silk robes with readable embroidery, only the ornaments written in the character description,
three-quarter view, beautiful delicate attractive faces (every young character must look pretty or handsome),
not glossy, not hyper-detailed Chinese game CG, not cool blue-white skin, not heavy dramatic makeup,
not old-fashioned, not overly ornate, no dense busy patterns, not photorealistic, not chibi.
head-and-shoulders portrait, three-quarter view, plain white background, 1:1 square, 1024x1024.
modest fully closed collar, no cleavage, no emphasis on chest. no text, no watermark. Fictional Chinese-style clothing, no Joseon clothing. Entire hairstyle inside frame. Hand-drawn 2D illustration with clearly visible brown contour ink, matte untextured skin color fills, simple two-tone cel shadow shapes, no airbrushed face modeling, no skin specular shine. beardless round chubby face, narrow crescent-shaped smiling eyes, faint rounded eyebrows, round nose, wide fawning smile, man in his 50s. dark red eunuch robe and black eunuch hat. Main color dark red. Soft round plump cheeks and round jaw, completely beardless, slightly bowing neck with ingratiating friendly smile. No jewelry or gold crown. Plain formal robe with restrained detail.
```

#### yeona

```text
The attached images show clothing only. Use them only as a reference for line art, coloring, shading and rendering quality. Do not copy any face. Korean webtoon character illustration, warm ivory paper-like overall tone,
clean dark-brown ink outlines of medium weight, slightly thicker contour lines around the face and body,
soft flat cel shading with gentle warm shadows (not painterly, not glossy 3D rendering),
warm peach-beige skin with a soft natural blush, light natural makeup,
eyes drawn with clear dark upper lash lines, warm-toned irises with one small highlight,
long hair drawn with many fine individual line strands and a few loose wisps,
muted warm palette with one clear accent color per character,
silk robes with readable embroidery, only the ornaments written in the character description,
three-quarter view, beautiful delicate attractive faces (every young character must look pretty or handsome),
not glossy, not hyper-detailed Chinese game CG, not cool blue-white skin, not heavy dramatic makeup,
not old-fashioned, not overly ornate, no dense busy patterns, not photorealistic, not chibi.
head-and-shoulders portrait, three-quarter view, plain white background, 1:1 square, 1024x1024.
modest fully closed collar, no cleavage, no emphasis on chest. no text, no watermark. Fictional Chinese-style clothing, no Joseon clothing. Entire hairstyle inside frame. Hand-drawn 2D illustration with clearly visible brown contour ink, matte untextured skin color fills, simple two-tone cel shadow shapes, no airbrushed face modeling, no skin specular shine. small heart-shaped face, medium-size round single-lidded dark brown eyes, short straight eyebrows, small nose, medium lips, faint freckles across the nose. woman of 22, a young adult not child, pretty delicate adult facial proportions, earnest worried look. brown hair in a neat palace maid's double bun with green ribbons (no jewels), simple light green palace maid's robe with a white sash, plainer than the consorts. Main color light green. No earrings, no hairpins, no crown, no embroidered ornament. Medium eyes with monolids, not oversized doe eyes; narrow small heart chin and distinct short horizontal brows.
```


- ref의 기존 얼굴 전부 `_work/old/face_v1/`로 이동. 저장 전이던 정덕비·소아·허어의 이전 생성본도 구본으로 분류.
- PROMPTS.md 수정된 2장과 4장 얼굴 규칙 재독. 이전 그림체 문장과 프롬프트는 폐기 기록이며 재사용하지 않음.
- 새 기준: 따뜻한 아이보리·진갈색 외곽선·무광 셀 채색·옅은 화장·3/4 각도. 옷 참고 두 장만 첨부. 정덕비 하늘색 유지.

### 얼굴 v2 검수 완료

- [x] 9장 각각 확정 시트 다섯 장과 나란히 배치해 따뜻한 피부 바탕·진갈색 외곽선·무광 셀 채색·옅은 화장을 확인. 하 귀비는 인물 지정 붉은 선만 얇게 유지.
- [x] 서로 얼굴 비교: ha 중간 아몬드눈/높은 광대, on 처진 좁은 눈/긴 계란형, jeong 작은 홑꺼풀/또렷한 턱/턱 점, baek 큰 쌍꺼풀/역삼각, sohwa 큰 치켜뜬 눈/계란형, soa 둥근 큰 눈/볼살/보조개, yeona 중간 홑꺼풀/작은 하트형/주근깨. heo 긴 얼굴·수염, bok 둥근 얼굴·수염 없음·실눈.
- [x] `ref/ha_face.webp`, `ref/on_face.webp`, `ref/jeong_face.webp`, `ref/baek_face.webp`, `ref/sohwa_face.webp`, `ref/soa_face.webp`, `ref/heo_face.webp`, `ref/bok_face.webp`, `ref/yeona_face.webp`: 모두 1024×1024 WebP.
- [x] `_work/faces_check.webp`: 코드 이름 포함 3×3 확인용 이미지, 1536×1632.
- [x] 확정 시트 5장 SHA256 일치 확인. PROMPTS.md는 읽기만 함.
- **얼굴 확인 대기. 여기서 중단. 시트 미제작.**

- 2026-11-17: c/soyun/14.webp (침소 버전, 엎드려 내려다보는 구도) 작가 확정. 다시 만들지 않음.

### 2026-11-17 사건 그림 9-1 개정 반영

- [x] `PROMPTS.md` 9-1과 2번 그림체 블록을 다시 읽고, 원문은 수정하지 않음. 작업 전후 SHA256 `a9d43c3a32edaeb978e76cfd0a8b09fcf91600a9741ab91505a9a3350b1a0d06` 일치.
- [x] `e/2.webp`, `e/25.webp`, `e/26.webp`: 각각 `p/2.webp`, `p/3.webp`, `p/4.webp`를 첫 첨부, `ref/bok_sheet.webp`를 둘째 첨부로만 사용해 재생성. 주인공 없이 복 공공을 중앙 동일 비율로 두고, 시트의 검은 내관모·팥색 교차 깃·금사 자수를 유지. 빈 교지와 단계별 궁인·하사품 구성을 반영.
- [x] `e/3.webp`: 받침과 손잡이 없는 작은 하얀 백자 찻잔으로 수정.
- [x] `e/4.webp`: `p/4.webp`와 `ref/soa_sheet.webp`만 첨부. 주인공은 먼 앞쪽의 화려한 쪽빛·금사 모란 덩굴 복장 뒷모습(봉황·용·관 없음), 연아는 연두색 시녀복 뒷모습으로 뒤따르게 함. 그 뒤로 함을 양손으로 든 시녀 세 명을 모두 뒷모습의 행렬로 배치하고 가방은 제외. 임소아는 왼쪽 먼 회랑 기둥 곁의 작은 하늘색 인물로 배치.
- [x] 다섯 장 모두 16:9 `1280×720` WebP 확인. 교체 전 파일은 `_work/old/e_v1/*_before_latest_20261117.webp`, 이전 모음은 `_work/old/e_v1/6_e_1_before_latest_20261117.webp`에 보존.
- [x] 사건 그림 12장(`e/1`~`e/10`, `e/25`, `e/26`)을 `_work/check/6_e_1.webp`로 다시 구성하고 누락·배치 확인.

### 2026-11-17 e/8 비 책봉 개정

- [x] `PROMPTS.md` 최신 9-1의 8번과 2번 그림체 블록을 다시 읽고 원문은 수정하지 않음.
- [x] `p/5.webp` 한 장만 첨부해 `e/8.webp` 재생성. p/9의 연분홍 휘장·모란 장식 병풍과 좌대·붉은 기둥·금장·등롱 배치를 구도 참고로 반영해 처소 내부 장면으로 구성.
- [x] 주인공은 화려한 쪽빛 회청색 교차 깃과 금사 모란·덩굴 자수, 금 비녀·보석 장식의 높은 올림머리. 봉황·새·용·황후 관은 제외.
- [x] 정면의 둥근 불투명 비단 단선이 눈·눈썹·코·볼·입·턱과 얼굴 윤곽 전체를 가리고, 부채 위로 머리와 장식만 보이는지 확인.
- [x] 교체 전 파일을 `_work/old/e_v1/8.webp`로 보관. 새 파일은 16:9 `1280×720` WebP로 저장하고 12장 모음 `_work/check/6_e_1.webp`에 반영.

### 2026-11-17 이벤트 2차 및 e/16 즉위식 개정

- [x] `PROMPTS.md`의 최신 2번 그림체, 8번 장소, 9-1 만드는 방법·목록을 다시 읽고 원문은 수정하지 않음.
- [x] 기존 `e/11`~`e/15`, `e/18`을 최신 지시와 대조. 공주·황자 강보, 사람 없는 빈 요람·신발, 냉궁 문틈, 빈 용상의 두 그림자, 비 오는 빈 마당과 비녀 조건을 충족해 재사용.
- [x] `e/27`: `ref/heo_sheet.webp`만 첨부. 휘장 아래 주인공의 쪽빛 회청색 소매·손목만 보이고, 갈색·쑥색 복장의 허 어의가 손끝으로 진맥하며 놀라는 장면으로 교체. 몸·배·얼굴은 제외.
- [x] 최신 목록에서 `e/28`이 삭제되어 새 후보는 사용하지 않고 기존 파일도 임의 삭제하지 않음. 2차 확인판에서는 제외.
- [x] `e/29`: `ref/soyun_sheet.webp`만 첨부. 밤 산실 밖의 닫힌 붉은 휘장과 아래 문틈 등불, 검보라·금색 복장의 소윤 옆모습만 배치. 산실 내부·출산 장면은 제외.
- [x] `e/17`: `p/22.webp`와 `ref/yukhan_sheet.webp`만 첨부. 새벽 뒷문을 나서는 말 한 필에 육한과 주인공 두 명만 뒷모습으로 배치. 추가 말·추가 인물 없음.
- [x] `e/16`: 최신 9-1 개정과 작가 참고 이미지의 대칭 행렬 구도를 반영. `ref/sodam_sheet.webp` 한 장만 첨부하고 배경은 글로 구성. 은발·옅은 금빛 눈을 시트와 맞추고, 검정·진홍 당나라식 면복, 금실 용 자수, 흰 옥 홀, 얼굴이 비치는 면류관 구슬 줄, 중국풍 정전의 황금 유리기와·붉은 기둥, 좌우 진홍 관복 신하 행렬을 확인. 주인공·글자 없음.
- [x] 직전 용상 e/16 후보는 `_work/old/e_v1/16_throne.webp`로 보관. 교체된 e/17·27·29 구본은 `_work/old/e_v2_before_latest/`에 보관.
- [x] 유효한 2차 10장(`e/27`, `e/29`, `e/11`~`e/18`)을 번호와 함께 `_work/check/6_e_2.webp`에 구성. 모두 16:9 `1280×720` WebP 확인.
- [x] e/16 면류관 머리 수정: 은발을 면류관 아래의 높은 관례용 상투로 모두 올리고, 어깨·가슴으로 내려오는 묶음머리와 땋은 머리를 제거. 얼굴·옅은 금빛 눈·면류관 구슬·중국풍 즉위 행렬은 유지. 직전 풀어 내린 행렬본은 `_work/old/e_v1/16_procession_hairdown.webp`로 보관하고 2차 확인판 갱신.
- [x] e/9·e/10 그림체와 색감 통일: 기존 구도와 e/9의 떨어진 봉황 비녀, e/10의 황후 뒷모습·봉황관·엎드린 궁인을 유지하면서 거친 사실화 질감, 갈색 안개, 무거운 암부를 제거. e/8을 그림체·색감 기준으로 사용해 선명한 웹툰 선, 부드러운 3~4단 셀 명암, 따뜻한 아이보리·연진홍·금빛 저대비 팔레트로 수정. 구본은 `_work/old/e_v1/9_before_style_fix.webp`, `10_before_style_fix.webp`에 보관하고 `_work/check/6_e_1.webp` 갱신.

### 2026-11-17 e/19·e/24 개정 및 배경 규칙 반영

- [x] 최신 9-1 배경 규칙 재독: p/ 그림은 분위기·건축 양식 참고이며, 장면에 맞춰 각도·거리·시간대를 새로 구성할 수 있음. 같은 장소는 기와·기둥·담장 색과 양식만 통일. `PROMPTS.md`는 수정하지 않음.
- [x] `e/19.webp`: `ref/soyun_sheet.webp` 한 장만 첨부. 중국풍 황궁 돌길에 내려놓은 밀폐형 목조 가마와 받침·가마채를 새로 구성. 소윤은 가마 안에 자연스러운 성인 좌상 비율로 한 명만 배치. 회색 내관은 다른 작은 얼굴로 휘장만 들고, 가마꾼 네 명은 가마채 양옆에서 다리를 접어 무릎 꿇음. 주인공은 이마를 땅에 댄 완전한 뒷모습으로 얼굴·옆얼굴 없음.
- [x] `e/24.webp`: `ref/sodam_sheet.webp` 한 장만 첨부. 밤 호숫가 정자에서 소담을 화면 중앙의 중간 근접 구도로 크게 배치. 촛불 하나, 흐린 등롱·달빛 수면, 탁자 전체에 펼친 글자 없는 단일 궁 지도, 그 위의 접힌 부채, 아래 가장자리의 작고 자연스러운 쪽빛 회청색 소매·손을 반영.
- [x] 교체 전 파일은 `_work/old/e_v1/19.webp`, `_work/old/e_v1/24.webp`에 보관. 두 파일은 16:9 `1280×720` WebP로 저장하고 `_work/check/6_e_3.webp`를 e/19~24 여섯 장으로 갱신.
- [x] e/19 원근·비율 추가 수정: 가마를 네 받침 위에 내려놓고 네 가마꾼을 가마채 양옆에서 무릎 꿇린 상태로 유지. 소윤을 좌석 깊숙이 약 18% 작게 배치해 머리가 가까운 내관과 같거나 조금 작고, 가마 내부 위·양옆에 여백이 생기도록 성인 좌상 비율을 보정. 직전 중간본은 `_work/old/e_v1/19_before_scale_fix.webp`에 보관하고 3차 확인판 갱신.

### 2026-11-17 프롤로그·상세 설명

- [x] `PROMPTS.md` 최신 1번 검열 규칙, 2번 그림체, 6번 프롤로그, 7번 상세 설명, 9-1 배경 규칙을 다시 읽고 원문은 수정하지 않음. 완료 시 SHA256 `5c4a9dd8ce781105a3e7b799c2b4cd000b24f143f72a72c3f8a71e28d8b58a60` 확인.
- [x] `pro/1.webp`~`pro/4.webp`: 붉은 담장 사이 두 후궁의 완전한 뒷모습, 소윤·육한의 중국풍 황제 행렬, 사람이 없는 낡은 처소, 연아와 받침 없는 백자 찻잔 장면을 16:9 `1280×720` WebP로 제작.
- [x] `d/1.webp`~`d/3.webp`, `d/5.webp`: 얼굴이 전혀 보이지 않는 주인공 표지, 백자 찻잔과 은비녀, 소윤·소담·육한 세 남자, 엎어진 백자 찻잔·찻물·협죽도 꽃잎·쪽빛 치맛자락을 2:3 `800×1200` WebP로 제작. d/3 부채의 글자처럼 보이는 획을 제거해 완전한 무지 부채로 수정하고, d/5의 불필요한 꽃병·꽃가지를 제거해 흩어진 꽃잎만 남김.
- [x] 최신 d/4 변경을 반영해 생성 AI 합성본은 사용하지 않고 `_work/old/d_v1/4.webp`로 보관. `c/wi/1.webp`, `c/ha/1.webp`, `c/on/1.webp`, `c/jeong/1.webp`, `c/baek/1.webp`, `c/soa/1.webp` 원본을 PIL로만 잘라 위·하·온·정·백·소아 순서의 2열×3행으로 합침. 머리 장식부터 가슴까지 같은 배율과 눈높이를 맞추고 4px 금빛 `#C9A45C` 안팎 테두리를 적용. 글자 없음.
- [x] 9장 모두 노출·글자·피·경고 표시·독성 연기 없이 검열 조건을 재확인. 주인공 얼굴 없음, 중국풍 황궁의 붉은 기둥·담장과 황금빛 기와를 확인.
- [x] 9장을 번호와 함께 `_work/check/8_pro_d.webp` 3×3 확인판으로 갱신. 모든 pro 파일은 1280×720, 모든 d 파일은 800×1200임을 확인.


### 2026-11-17 썸네일 후보 3장

- [x] 작가 선택: 3번 `thumb/3.webp`.
- [x] `PROMPTS.md`의 7-1번 썸네일, 1번 공통·검열 규칙, 2번 스타일 블록 재독. 원문 SHA256 `5c4a9dd8ce781105a3e7b799c2b4cd000b24f143f72a72c3f8a71e28d8b58a60` 유지.
- [x] 내장 `image_gen`에 `ref/soyun_sheet.webp` 한 장만 첨부하고 아래 동일 프롬프트로 세 번 생성. `thumb/1.webp`~`thumb/3.webp`를 2:3 세로 800×1200 WebP로 저장.
- [x] `_work/check/9_thumb.webp`에 왼쪽부터 1~3번을 배치. 윗줄은 원본 전체, 아랫줄은 각 원본의 상하 200px씩을 뺀 중앙 정사각형.
- [x] 시트와 대조. 세 후보 모두 얼굴의 특징과 금빛 눈, 검보라빛 흑발과 복식, 금관의 보석·가로 장식·한쪽 술, 금색 용과 구름 자수를 재현함. 정면 구도와 조명에 따라 이목구비와 색조에 소폭 차이가 있음.
- [x] 세 크롭 모두 얼굴과 백자 찻잔이 들어오고 금관 상단은 잘림. 원본 세 장 모두 단정한 옷깃, 받침 없는 무지 백자, 옅은 김, 분홍 꽃잎을 확인. 글자, 피, 직접적인 독 묘사, 쓰러진 인물 없음. 2번 상단과 3번 하단에는 흩날리는 꽃잎 외에 꽃가지도 보임.

#### 공통 생성 프롬프트

```text
Use the attached reference sheet only for this man's face, black hair, gold crown, outfit colors and embroidery. Copy them exactly.

Korean romance-fantasy webtoon illustration, moderately simplified anime line art,
hair drawn in smooth clumps with a moderate amount of strand lines and only a few loose strands,
nose with a small soft shadow and a light line, lips with soft color and one small highlight,
cel shading with three or four soft-edged tones, fabric patterns visible but not dense,
subtle shine only on gold ornaments and hair, detailed beautiful eyes as the main focus,
soft muted colors, low contrast, natural soft skin without glow,
beautiful attractive faces (every young character must look pretty or handsome), slim graceful builds,
natural elegant webtoon body proportions: about seven and a half heads tall, head size natural (not tiny, not big), neck natural length, shoulders about twice the head width (not narrow or sloping), natural waist about three heads below the top of the head (not right under the chest), legs about four and a half heads, arms long enough that the clasped hands rest just below the sash, legs in normal proportion (not stretched, not elongated, not chibi, not short), robes drape along the body instead of looking boxy,
women wear layered cross-collar silk palace robes that wrap left over right, with a white inner collar, very wide long flowing sleeves, a long outer robe trailing to the floor, a sash at the waist, gold-thread embroidery flowing along the robe and sleeves (no standing collar, not a qipao),
men wear cross-collar silk robes that wrap left over right,
only the ornaments written in the character description,
fictional Chinese-style imperial palace setting, white or soft blurred background,
no text, no watermark, not realistic, not overly detailed, not flat, not neon, no plastic shine, not chibi (except gag faces)

Book-cover style portrait of the young emperor, chest-up, facing the viewer directly. He extends one hand toward the viewer, offering a plain white porcelain tea cup without a saucer; a thin wisp of steam rises from it. A faint smile at one corner of his mouth, calm, indifferent and dangerous eyes looking straight at the viewer. A few pink oleander petals drift near the cup. Background: softly blurred red pillars and gold of an imperial Chinese throne hall, darker toward the edges. His face and the cup are close together in the center of the frame, so the image still works when cropped to a square. Most beautiful and handsome, highest finish. No text, no blood, no exposed skin, no one collapsing.

One standalone illustration, 2:3 vertical portrait. Fit the whole gold crown, face and cup within the centered square crop by reserving sufficient space above the crown and placing the cup just below and slightly off to one side of his chin, unobstructed. Preserve the reference's amber-gold eyes, gold crown with side tassel, dark black-purple robe, gold dragon and cloud embroidery, and white inner collar. Modest fully closed collar, no cleavage, no emphasis on chest. The face and cup-offering hand are naturally visible. Fictional Chinese-style empire of Daeryeong, no real dynasty emblems, no signs or lettering, no other people, no visible poison.
```

### 2026-11-17 포스터

- [x] `PROMPTS.md` 7-2절을 다시 읽고 이번 요청에서 지정한 `thumb/2.webp` 한 장만 바탕으로 사용. `PROMPTS.md` 수정 없이 SHA256 `637d9518ce6ee3f6ce92dca918ba53e4995c184c012e5324a44c0f0a22b6cedd` 확인.
- [x] 내장 image_gen으로 궁전 배경과 어두운 아래 여백 확장. 생성 시안에서 달라진 이목구비와 자수를 복원하기 위해 확장부에만 생성 결과를 쓰고, 중앙에는 썸네일 2번의 800×1200 픽셀 전체를 배치. 만나는 경계는 원본 바깥에서만 보정.
- [x] 설치된 애플명조(AppleMyungjo Regular)로 PIL에서 제목을 두 줄 가운데 정렬. 옅은 금색 `#E8C987`과 약한 어두운 그림자를 적용. `poster/1.webp`는 상단, `poster/2.webp`는 하단.
- [x] `poster/base.webp`, `poster/1.webp`, `poster/2.webp` 모두 1040×1560 무손실 WebP. 세 파일 중앙 영역의 RGB 픽셀이 `thumb/2.webp`와 완전히 일치하고 제목이 얼굴·금관·찻잔과 겹치지 않음을 확인. `_work/check/10_poster.webp`는 왼쪽부터 바탕, 상단 제목, 하단 제목.

#### 배경 확장 프롬프트

```text
Edit the attached image into a vertical 2:3 poster. Keep the man, his face, hair color (keep the current dark hair with a purple tint), crown, robe, hand and the tea cup exactly as they are — do not redraw or restyle him. Extend the canvas: add more space above his crown with dark, softly blurred red pillars, golden throne-hall details and drifting pink oleander petals, and add more space below with the dark robe fading into deep shadow. Leave the top area and the bottom area calm and dark enough for a title to be placed later. No text, no letters, no logo.

Outpaint the outer edges only. Preserve the complete original rectangular artwork including all visible parts of the man at their original relative positions, at about 77% of the output height and width, centered horizontally and vertically. Continue the artwork seamlessly at all four edges so the result remains 2:3. The upper and lower blank areas should each accommodate two lines of center-aligned text later. Keep the middle of each new title area dark, and place a few small petals and muted architecture toward the top edges.
```

#### 포스터 이목구비와 표정 보정

- [x] `ref/soyun_face.webp`의 눈썹, 반쯤 내리뜬 금빛 눈, 코끝, 미소 없이 살짝 벌어진 입매를 포스터의 정면 시선에 맞춰 반영. 내장 image_gen으로 얼굴 부분을 편집하고 그 부분만 세 포스터에 동일하게 합성.
- [x] `poster/base.webp`, `poster/1.webp`, `poster/2.webp`, `_work/check/10_poster.webp` 갱신. 세 포스터의 얼굴 마스크 바깥 픽셀과 기존 제목이 보정 전과 일치함을 검증. `PROMPTS.md` 원문 유지.

```text
Edit the face inside IMAGE 1, the square crop of the current poster. IMAGE 2 is the exact reference for both the fictional emperor's facial features AND EXPRESSION. His expression in IMAGE 2 is aloof, composed, faintly disdainful and UNSMILING. Copy the expression closely: the upper eyelids hang low over the amber irises, his eyes are long and narrowed in a languid half-lidded gaze, his brows are relaxed and almost straight, the upper lip is sharply shaped and slightly asymmetric, the lower lip is soft, there is a tiny dark relaxed separation between the lips, and neither mouth corner is pulled up into a smile. Preserve the firmness and delicacy of the brows, fine nose tip and mouth from IMAGE 2. The difference from IMAGE 1 must be clearly visible in the eyelids and lips. Translate this same expression naturally onto IMAGE 1's near-frontal head and direct gaze, without importing the three-quarter view, rotating the face, looking aside, or changing the head position. Manually redraft only facial features and their subtle shading, preserve the original frontal face outline, cheeks, ears, skin tone, existing face-crossing strands, existing dark purple-black hair, crown details, collar and background of IMAGE 1. Preserve the crop framing, position and scale. No text.
```

#### 첨부 포스터 색채와 선 보정

- [x] 첨부 `포스터.png`를 작업 대상으로, `ref/soyun_face.webp`를 색과 선의 기준으로 사용. 내장 image_gen으로 분홍 역광과 주황빛 반사를 누르고, 검보라 머리와 옷의 명암 및 가는 갈색 선을 부드럽게 조정.
- [x] `poster/style.webp`에 1024×1536 무손실 WebP로 저장. 원본의 제목과 장식이 놓인 하단 영역의 RGB 픽셀이 전부 일치함을 검증. `PROMPTS.md` 원문 유지.

```text
IMAGE 1 is the exact finished poster to retouch. IMAGE 2 is the exact visual style swatch for this retouch. Do a restrained paintover of IMAGE 1 to bring its illustration's color, linework, and soft shading into the same world as IMAGE 2. Closely match the actual rendering in IMAGE 2: warm porcelain-peach skin, softly layered blush and gradients with clear but soft shadow edges, fine tapered dark brown ink (especially on facial contours, eyelashes and flowing hair), nearly-black plum hair with soft dusky mauve highlights, sumptuous dark plum-charcoal fabric, soft antique honey-gold metal and fine crisp gold threadwork. Maintain the dimensional quality, graduated soft cel shading and selective soft sheen that are plainly present in IMAGE 2. This is a small tonal adjustment toward the specific reference, not a genre conversion. Avoid flat posterized blocks, harsh black contour outlines, muddy gray hues, and exaggerated neon rim lighting. Only dampen the brightest pink-white rim light and orange cast of IMAGE 1 toward IMAGE 2's muted warm palette. Keep the red-and-gold palace dark and softly blurred. 

Keep IMAGE 1's exact canvas, facial features, half-lidded expression, chin angle, hair and crown geometry, sleeve and embroidery, reaching hand and white tea cup, drifting pink petals, steam, foreground/background balance, and entire gold Korean title and ornament unaltered in geometry and placement. The reference's white background, layout, and pose do not belong in the poster. Full poster 1024:1536.
```

#### pro/2 육한 기승 옆모습 보정

- [x] 원본 `pro/2.webp`를 `_work/old/pro_v1/2.webp`로 백업하고 바이트 일치를 확인. `PROMPTS.md` 유지.
- [x] 최종 요청에 따라 원본의 말을 탄 장면을 바탕으로 수정. 내장 image_gen에 원본 `pro/2.webp`와 `ref/yukhan_sheet.webp` 두 장만 첨부. 육한의 몸과 얼굴을 말이 향하는 오른쪽으로 맞추고, 황제 쪽으로 돌아보던 시선을 전방 옆모습으로 조정.
- [x] 얼굴 윤곽과 깊은 남색 머리, 상투, 갑옷을 시트와 대조. 말의 머리와 자세, 가마, 황제, 행렬과 궁궐 배경을 원본으로 유지하고 육한의 상체와 손이 쥔 고삐가 이어지는 부분만 합성. `pro/2.webp`는 1280×720 무손실 WebP로 저장.
- [x] `_work/check/8_pro_d.webp`에서 pro/2 칸만 교체하고 나머지 픽셀이 기존 비교판과 동일함을 확인.

```text
Edit IMAGE 1, the exact original illustration of a Chinese-fantasy imperial procession. IMAGE 2 is the exact design and identity reference for the mounted commander. Keep the black horse, its forward pose toward screen-right and into the palace, its head, mane, reins, saddle and all tack exactly as shown. Keep the commander seated in the same saddle. Modify only the mounted commander's torso, shoulders, neck and head to remove the awkward twist. His hips, waist, chest, shoulders and head now all naturally align with the horse's direction, screen-right and slightly into the courtyard. Show the commander in clear right-facing side profile, with his visible eye looking right, past the horse's head into the palace courtyard. The nose points toward the right edge. He is not glancing at the emperor on the left or toward the camera. Keep both hands natural on the reins; retain their current position where possible. Preserve the original rider's position and scale; no walking, no new figures, no new horse. Copy the second reference's exact recognizable angular face translated to this right-facing profile, tied deep indigo hair, dark slate lamellar armor, muted antique gold trim, dark robe and restrained colors. Leave the entire sedan, emperor, bearers, kneeling crowd, buildings, paving, sunlight, colors, perspective and the rest of the scene as they are in IMAGE 1. Original 16:9 composition.
```
