# hg — 「후궁에 들어갔더니 매일 독을 마신다」 이미지 지시서

크랙 작품 「후궁에 들어갔더니 매일 독을 마신다」에 쓰는 이미지를 만든다. 이 파일이 작업 지시서다. 위에서부터 순서대로 따른다.

> **이 파일은 읽기 전용이다. Cursor는 이 파일을 고치지 않는다.**
> 진행 상황, 만든 번호, 건너뛴 번호, 메모는 모두 `PROGRESS.md`에만 적는다.
> 지시서에 틀린 곳이나 애매한 곳이 있으면 고치지 말고 `PROGRESS.md`의 「질문」 칸에 적고 그 항목은 건너뛴다.

- 저장소: `hg` (GitHub Pages로 공개)
- 링크 형식: `https://baobao-jane.github.io/hg/폴더/파일.webp`
- 기준 문서: 「후궁에 들어갔더니 매일 독을 마신다 — 크랙 설정집」 (Claude Docs). 인물 외형·이미지 목록이 바뀌면 작가가 이 파일을 고친다.

---

## 0. 시작 전 확인 (작가 확정 대기)

- [x] 그림체 다시 고름 (2026-11-12): 시험 1번 한국 로판 웹툰 표지풍 (2번 → 3번 → 1번으로 최종). 크랙 궁중물 상위작에 가장 많은 계열이라 골랐다. 기준 그림 `_work/style_test/1_ha.webp`, `1_soyun.webp`. 소윤의 **얼굴은 옛 확정 시트(`soyun_sheet.webp`, 11-02 흑발 v2)의 얼굴을 그대로 쓴다** (2026-11-12 작가 결정). 그 시트 한 장만 첨부해 얼굴을 유지하고 그림체만 1번으로 다시 그린다. 시험 그림 `1_soyun`의 얼굴은 쓰지 않는다. **옷깃만 따르지 않는다** (시험 그림은 치파오 깃, 실제로는 앞에서 여미는 깃).
- 기존 ref/ 시트와 얼굴은 모두 옛 그림체라 쓰지 않는다. 14명 모두 새 그림체로 다시 만든다.
- 주인공 나이: 입궁 때 23세 (2026-11-03). 소화 24세, 연아 22세, 임소아 22세로 맞춘다.
- [x] 주인공({user}) 얼굴은 그리지 않는다 (뒷모습·실루엣·손만). 주인공 옷은 수수한 쪽빛 회청색 교차 깃 겉옷, 품계가 오를수록 금빛 자수가 늘어난다.

---

## 1. 공통 규칙

### 파일
- 형식: webp, 한 장 300KB 안팎
- 파일명은 숫자만 쓴다. 예: `c/soyun/1.webp`, `p/4.webp`
- 목록에 없는 번호는 만들지 않는다

### 비율 (크랙 채팅은 이미지를 글 폭에 맞춰 보여 줘서, 채팅용은 모두 가로로 만든다)

| 폴더 | 용도 | 비율 | 권장 크기 |
| --- | --- | --- | --- |
| `c/` | 인물 표정 | 4:3 가로, 가슴 위 클로즈업 | 1200×900 |
| `i/` | 소품 | 16:9 가로, 소품은 가운데에 작게 | 1280×720 |
| `p/` `s/` `e/` | 장소·상황·이벤트 | 16:9 가로 | 1280×720 |
| `pro/` | 프롤로그 (크랙 내부 등록) | 16:9 가로 | 1280×720 |
| `d/` | 상세 설명 (크랙 내부 등록) | 2:3 세로 | 800×1200 |
| `ref/` | 캐릭터 시트 (작업용) | 3:2 가로 | 1500×1000 |

### 반드시 지킬 것
- {user}(주인공)의 얼굴은 그리지 않는다. 필요하면 뒷모습, 실루엣, 손, 화면 밖으로만 둔다. `c/`에 주인공 폴더는 없다.
- 배경은 **가상의 중국풍 제국 대령(大寧)**. 실제 왕조의 상징(실존 황제의 용포 문양, 실존 궁궐 현판)을 그대로 쓰지 않는다. 한국 조선 궁중 복식(한복 당의, 조선 왕의 익선관)과 섞지 않는다.
- 특정 드라마·애니메이션·만화 작품의 이름이나 그 작품의 인물을 프롬프트에 쓰지 않는다. 기존 작품 인물과 닮게 만들지 않는다.
- 그림 안에 글자를 넣지 않는다. 교지, 서찰, 장부, 현판은 글자 없이 빈 종이나 알아볼 수 없는 획으로.
- **모든 이미지(채팅용 외부 링크 포함)**: 노출과 가슴을 강조하는 구도는 금지한다. 옷깃은 단정하게 여민다 (`modest fully closed collar, no cleavage, no emphasis on chest`). 외부 링크는 크랙 검열을 거치지 않지만 작품은 세이프 등급이므로 같은 기준을 지킨다.
- 황상을 모시는 밤, 목욕, 회임, 출산은 장면을 그리지 않는다(가마, 등불, 빈 욕조, 강보처럼 앞뒤만). 목욕간(p/29)은 사람 없이 장소만.
- **썸네일·`d/`·`pro/`는 크랙 내부에 등록되어 검열을 받는다.** 만든 뒤 한 번 더 본다: 노출, 장신구·소품의 글자, 핏자국, 독을 직접 보여 주는 표현이 없는지.
- 독과 죽음은 직접 그리지 않는다. 피는 쓰지 않고, 엎어진 찻잔, 떨어진 비녀, 빈 자리, 그림자로 보여 준다.
- 독 이미지는 만드는 법이나 양을 보여 주지 않는다. 찻잔, 향낭, 꽃처럼 이야기 속 물건으로만.
- 인물 이미지는 반드시 그 인물의 `ref/` 시트를 첨부해 만든다. 얼굴·머리색·눈 색·옷 색이 시트와 어긋나면 다시 만든다.

---

## 2. 그림체 (2026-11-12 최종 — 시험 1번 + 선 「반반」)

모든 프롬프트 앞에 붙인다.

```
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
```

- 2026-11-03 오후: 확정 시트(soyun, sodam, yukhan, dan, wi)의 실제 그림체를 보고 다시 썼다. 따뜻한 아이보리 톤, 진갈색 잉크 외곽선, 납작한 셀 채색, 따뜻한 피부, 옅은 화장, 3/4 각도. 오전 문장은 광택 많은 중국 게임 CG풍으로 흘러서 폐기했다. 젊은 인물은 모두 예쁘거나 잘생겨야 한다.
- 2026-11-03 오전 수정(폐기): 요즘 한국 로맨스판타지 웹툰 수준으로, 촌스럽지 않게. 모든 인물에 같은 눈매를 입히던 문장(sharp elegant narrow eyes…, half-lidded calm gaze, subtle faint smile)과 모든 인물에 금실 자수·귀걸이·비녀를 붙이던 문장을 뺐다. 눈매·표정·장신구는 인물 행에만 쓴다.
- 작가가 고른 참고 그림의 공통점: 가는 잉크 선, 흩날리는 머리카락 가닥, 길고 날카로운 눈매, 채도를 낮춘 색에 대표 색 하나, 흐린 안개 배경, 정교한 금·은실 자수.
- 참고 그림은 다른 작가의 작품이다. 프롬프트에 첨부하지 않는다. 그림체만 빌리고 얼굴과 인물은 닮게 하지 않는다.
- 참고 그림 일부의 노출·가슴 강조는 따르지 않는다 (1장 규칙).

### 궁중 분위기
- 붉은 궁 담장, 황금 기와, 긴 회랑, 비단 휘장, 등롱, 향로, 백자와 청자 찻잔
- 후궁의 처소는 품계가 오를수록 넓고 화려해진다(재인: 낡고 작은 방 → 비: 금빛 전각)
- 황실(황제, 정친왕, 장공주)은 금빛 눈으로 혈통을 보여 준다

### 표정 연출
- 평소엔 절제된 얼굴. 곁눈질, 반쯤 내리뜬 눈, 살짝 올라간 입꼬리로 속내를 보여 준다
- 8번(어이없음)만 순간적으로 크게 무너지는 코믹 표정으로 과장한다
- 배경은 인물의 대표 색을 연하게 깐 단색 그라데이션

---

## 3. 작업 순서 (2026-11-12 최종)

1. **얼굴** `ref/코드_face.webp` 14장 — 4장 「그림체 기준 그림」 방식. 기준은 `ref/ha_face.webp`.
2. **캐릭터 시트** `ref/코드_sheet.webp` 14장 — 자기 `_face`만 첨부해서. 4장 공통 시트 블록 + 「전신 비율」.
3. **인물 표정** `c/코드/번호.webp` 87장 — 자기 `_sheet` 첨부 + `ref/ha_face.webp`(그림체).
4. `pro/` 4장, `d/` 5장
5. `p/` 29장, `s/` 10장, `e/` 18장, `i/` 13장 — 인물이 나오면 그 인물의 `_sheet`를 첨부.
6. 단계가 끝날 때마다 `PROGRESS.md`를 갱신하고, 확인용 모음 이미지를 `_work/check/단계.webp`로 만든다.

---

## 4. 캐릭터 시트 `ref/코드_sheet.webp`

공통 (그림체 블록 뒤, 인물 설명 앞에 붙인다):

```
character reference sheet, pure flat white background, three panels side by side:
full body front view on the left, head-and-shoulders close-up in the center,
exact side profile full body on the right,
figures fill about 90% of the frame height, small margins, feet and hair ornaments fully inside the frame,
all three panels evenly spaced, nothing cut off at any edge,
expression as written in the character row, same outfit in all views,
no text, no letters, no labels, no title, no watermark, no captions
```

- 세 패널은 **같은 인물 한 명**이다. 가운데 얼굴을 기준으로 왼쪽·오른쪽 패널의 얼굴이 반드시 같아야 한다.
- **확정한 얼굴 (2026-11-12)**: soyun, sodam, ha, sohwa. 이 넷은 다시 만들지 않는다. (11-03의 시트 확정은 옛 그림체라 폐기)
- **다시 만들 것**: ha, on, jeong, baek, sohwa, soa, heo, bok, yeona (9명). 얼굴 먼저 → 작가 확정 → 시트 순서.

### 여자 복식: 교차 깃 넓은 소매 겉옷 (2026-11-12 최종 — 명나라풍 세운 깃, 당나라풍은 폐기)
- 작가가 지정한 참고 그림: `_work/ref_input/women_outfit_ref.webp` (옛 위 황후 시트). **옷 모양만** 따른다. 그림체와 얼굴은 따르지 않는다.
  - 흰 안깃이 보이는 **교차 깃**, 여러 겹 겹친 비단 옷
  - **바닥까지 늘어지는 아주 넓고 긴 소매**, 땅에 끌리는 긴 겉옷
  - 허리에 띠, 옷과 소매를 따라 흐르는 **금실 자수**(봉황, 덩굴, 꽃 등 인물 문양)
  - 장신구로 둥근 비단 부채(단선)를 들 수 있다
- 신분에 따라 다르게:
  | 인물 | 복식 |
  | --- | --- |
  | 태후 | 가장 무겁고 단정하게. 짙은 가지색 겉옷 여러 겹, 금실 단룡 원문 (소윤의 크게 휘감는 용과 다르게 작고 둥근 문양) |
  | 황후 | 가장 격식 있게. 진홍에 금실 봉황 자수가 옷 전체를 흐른다 (참고 그림 그대로) |
  | 4비 | 화려하게. 대표 색 겉옷에 금·은실 자수. 하 귀비가 가장 화려하다 |
  | 장공주 | 화사하고 가볍게. 벚꽃 분홍, 얇은 비단, 벚꽃 무늬를 **금실 자수**로 |
  | 임소아 (재인) | 가장 낮은 후궁. 소매가 덜 넓고 자수가 적다 |
  | 연아 (시녀) | 수수한 궁녀 옷. 교차 깃, 소매 좁게, 자수 없음, 앞치마 띠 |
- 가슴 노출이나 강조는 금지한다. 옷깃은 단정하게 여민다.
- 남자 인물은 교차 깃 비단 도포.

### 인물 색 (2026-11-12 확정 — 4장 인물 행의 `Main color`보다 이 표가 우선한다)

한 사람에 대표 색 하나. 비슷한 색은 한 명만 쓴다. 4비는 꽃 문양을 하나씩 갖는다.

| 코드 | 인물 | 대표 색 | 보조 색 | 문양 |
| --- | --- | --- | --- | --- |
| soyun | 황제 소윤 | 먹색 `#1F1D24` (ink black) | 금 `#C9A44C` | 용·구름 |
| sodam | 정친왕 소담 | 비취 옥색 `#7FB5A8` (jade green) | 은 `#C8CED3` | 구름 |
| yukhan | 육 통령 육한 | 옷: 짙은 강철색 `#3E4650` (dark steel grey) 갑옷 / 머리: 짙은 쪽빛 `#22304A` | 놋쇠 `#A6844A` | 없음 |
| dan | 태후 단씨 | 가지색 `#4B2E4F` (aubergine purple) | 금 | **금실 단룡 원문** (원 안에 몸을 만 작은 용, 가슴·어깨·소매에 몇 개씩. 2026-11-16, 학에서 바꿈) |
| wi | 황후 위씨 | 진홍 `#9E1B2B` (deep crimson) — 붉은색은 황후만 | 금 | 봉황 |
| ha | 하 귀비 | 호박빛 금색 `#D99A2B` (amber gold), 넓고 진하게 | 진주 흰색 | 모란 |
| on | 온 숙비 | 연보라 `#A893C4` (lavender) | 은 | 등꽃 |
| jeong | 정 덕비 | 청회색 `#6E7F8C` (blue-grey) | 백옥 `#EDEAE0` | 매화 |
| baek | 백 현비 | 흰색 `#F4F1EA` (ivory white) | 옅은 은회 `#C9CCD1` | 백련 |
| sohwa | 소화 장공주 | 벚꽃 분홍 `#F2A7C3` (cherry-blossom pink) | 금 | 벚꽃 — **금실 자수로만** (2026-11-12, 분홍·흰색 꽃 자수 아님) |
| soa | 임소아 | 하늘색 `#A9CFEA` (sky blue). 배신 뒤 장면은 같은 옷을 어둡고 차갑게 | 흰색 | 없음 |
| heo | 허 어의 | 약재 갈색 `#6B4F3A` (medicinal brown) | 쑥색 `#8A9468` | 없음 |
| bok | 복 공공 | 팥색 `#6E2F3A` (dull red-bean) — 황후 진홍보다 탁하게 | 검정 | 없음 |
| yeona | 연아 | 연두 `#B8D08A` (light yellow-green) — 초록 계열은 연아만 | 흰색 | 없음 |

- 금은 황제·태후·황후·장공주의 **보조 색**으로 얇게만 쓴다. 금을 옷 전체에 넓게 쓰는 사람은 하 귀비뿐이다.
- 주인공(얼굴 없음, 뒷모습·손만): 제안 — 처음엔 수수한 쪽빛 회청색, 품계가 오를수록 금빛 장식이 더해진다. (미확정)

### 채도·선 (2026-11-12 최종)
- 작가가 `_work/line_test/ha_line_compare.png`에서 **「반반 원본」**을 골랐다. 선은 원래 그림과 단순화의 중간, 색은 **추가 보정 없이** 그대로 쓴다. (채도 보정 A·B는 쓰지 않는다)
- 2장 그림체 블록이 이 기준으로 바뀌었다.

### 전신 비율 (2026-11-12 추가)
- 하 귀비 전신이 머리가 크고(약 5.5~6등신) 몸통이 짧고 옷이 상자처럼 퍼져서 비율이 무너졌다.
- 모든 성인 인물은 **약 7.5등신**: 머리 크기와 목 길이, 어깨 너비가 자연스럽게. (2026-11-12: "8등신, 작은 머리, 긴 목, 긴 다리"로 했더니 머리가 너무 작고 몸이 늘어난 약 10등신이 나와서 고침) 올린 머리와 장신구는 머리 길이에 넣지 않는다.
- 너무 짧아도(6등신 이하, 머리 큼) 안 되고 너무 길어도(9등신 이상, 머리가 작고 몸이 늘어남) 안 된다.
- **몸 부위별 기준 (2026-11-12 추가)**: 등신만 맞추면 위아래 균형이 무너진다. 머리 하나를 1로 잡고:
  - 어깨 너비: 약 2 (여자), 약 2.3 (남자)
  - 정수리에서 허리띠까지: 약 3 (허리띠는 가슴 바로 밑이 아니라 갈비뼈 아래, 자연스러운 허리 조금 위)
  - 허리띠에서 발끝까지: 약 4.5 (끌리는 치마 끝은 더 내려가도 된다)
  - 팔을 내리면 손끝이 허벅지 중간. 손을 앞으로 모으면 허리띠 바로 아래.
  - 목은 머리 길이의 약 1/3.
- **비율 기준 그림 (2026-11-12 12:04 작가 확정)**: `ref/ha_face.webp`(하 귀비 전신 최종). 재 보면 어깨는 머리 폭의 약 2배, 정수리에서 허리띠까지 머리 약 2.8개, 모은 손은 허리띠 바로 아래, 끌리는 치마 끝까지 합치면 약 9등신(치마가 바닥에 끌려서 길어 보이는 것). 다른 인물의 전신·시트는 이 그림과 머리 크기, 어깨 너비, 키 비율을 맞춘다.
- 옷은 몸을 따라 길게 떨어지게. 소매가 넓어도 몸통이 상자처럼 보이지 않게.
- 남자는 여자보다 머리 반 개쯤 크다. 육 통령이 가장 크다. 복 공공과 허 어의는 7등신 안팎.
- 시트와 전신 그림을 만들 때마다 머리 크기와 등신을 확인한다.

### 작가가 지정한 생김새 참고 그림
- bok: `_work/ref_input/bok_ref.webp` — 얼굴 생김새, 관모, 관복 모양을 그대로 따른다. 그림체만 ha_face에 맞춘다. 옷 색은 황후 진홍보다 탁한 팥색으로.

### 그림체 기준 그림 (2026-11-12 추가)
- 그림체 기준은 **`ref/ha_face.webp` 한 장**이다. = `_work/line_test/ha_mid.webp` 그대로 (2026-11-12 최종, 옷깃도 그대로). 선, 채색, 광택, 눈 하이라이트, 피부 표현을 이 그림에 맞춘다.
- 다른 인물을 만들 때 이 그림을 **두 번째 첨부**로 붙이고, 첫 번째 첨부는 **그 인물 자신의 얼굴**로 한다. 자기 얼굴이 아직 없으면 첫 번째 첨부 없이 ha_face만 붙인다.
- 프롬프트 맨 앞:
  ```
  Image 1 is this character: keep the face, age, hairstyle, outfit and colors exactly the same.
  Image 2 is an art style reference only: match its line art, glossy cel coloring, eye highlights, skin rendering and brightness exactly. Do not copy the face, hair or outfit from image 2.
  ```
  (자기 얼굴이 없을 때는 첫 줄을 빼고 "The attached image is an art style reference only: …"로 쓴다.)
- 사실화풍, 서양 만화풍, 수채풍, 광택 없는 반실사로 흐르면 다시 만든다.

### 얼굴이 닮아 보이지 않게 (2026-11-03 다시 정함)
이미지 AI는 예쁜 얼굴을 하나로 모으는 버릇이 있고, 다른 인물 그림을 첨부하면 그 얼굴을 따라 한다. 그래서 아래 순서를 지킨다.

1. **다른 인물의 그림은 절대 첨부하지 않는다.** soyun·dan·wi·ha 시트도, 참고 그림도 첨부하지 않는다. (11-03 오전의 「dan·wi·ha 세 장 첨부」 규칙은 폐기)
2. **얼굴 먼저**: 인물마다 `ref/코드_face.webp` 한 장을 먼저 만든다. 아무것도 첨부하지 않는다.
   - 프롬프트 = 그림체 블록에서 배경 줄을 뺀 것 + `head-and-shoulders portrait, three-quarter view, plain white background, 1:1 square, 1024x1024` + 아래 「이목구비 표」의 영어 문장 + 인물 행의 머리·옷 부분
   - 만든 뒤 작가가 확정할 때까지 시트로 넘어가지 않는다. PROGRESS.md에 「얼굴 확인 대기」로 적고 멈춘다.
3. **시트는 나중에**: 작가가 얼굴을 확정하면, **그 인물 자신의 `_face.webp`만** 첨부해서 시트를 만든다.
   - 프롬프트 맨 앞: `Draw a character reference sheet of the woman/man in the attached image. Keep her/his face exactly the same.`
4. 시트를 만들 때는 그림체 블록에서 배경 줄을 뺀다. 공통 시트 블록의 `neutral expression` 대신 인물 행의 `expression:`을 쓴다.
5. 장신구는 인물 행에 적힌 것만 그린다. 금관·술 장식·귀걸이를 모든 인물에 붙이지 않는다.
6. 시트가 다 모이면 얼굴만 보고 누가 누구인지 구별되는지 본다. 구별이 안 되면 그 인물만 2번부터 다시 한다.

### 이목구비 표 (어떤 두 사람을 골라도 세 군데 이상 다르게)

| 코드 | 인물 | 얼굴형 | 눈 | 눈썹 | 코·입 | 대표 특징 |
| --- | --- | --- | --- | --- | --- | --- |
| soyun | 황제 소윤 | 길고 갸름 | 반쯤 감긴 짙은 금빛 눈 | 곧고 짙게 | 곧은 코, 얇은 입 | 지루한 눈빛 (확정) |
| sodam | 정친왕 소담 | 소윤과 닮은 갸름한 얼굴이지만 턱선과 얼굴선이 더 부드럽고 매끈함 | 고양이상: 눈꼬리가 살짝 올라간 아몬드형, 소윤보다 크게 뜬 눈, 옅은 금빛(황실 혈통) | 소윤보다 가늘고 부드럽게 | 소윤과 같은 곧은 코, 다문 입 | 무표정이지만 부드러운 눈빛, 보조개 없음, 은발 |
| yukhan | 육 통령 육한 | 각진 턱 | 작고 깊은 회색 눈 | 굵고 곧게 | 곧은 콧대, 다문 입 | 왼뺨 흉터, 짙은 쪽빛 머리 (2026-11-12) |
| dan | 태후 단씨 | 갸름하고 날렵한 긴 얼굴, 높은 광대 | 길고 가는 눈, 무겁게 내리뜬 눈꺼풀, 검은색 | 가늘고 길게 그린 눈썹 | 오똑한 코, 얇고 단정한 입술 | 40대 초반, 마른 체형, 귀티. 눈가에 아주 옅은 잔주름만 |
| wi | 황후 위씨 | (확정) | | | | |
| ha | 하 귀비 | 하트형, 높은 광대 | 중간 크기 아몬드형, 길게 뺀 붉은 아이라인, 무겁게 내리뜬 호박색 눈 | 날카로운 아치형 | 오똑한 코, 붉고 도톰한 입술 | 눈 밑 점, 거만한 눈빛 |
| heo | 허 어의 | 길고 마른 얼굴, 꺼진 볼 | 작고 불안한 눈, 눈가 주름 | 옅고 처진 눈썹 | 긴 코, 얇은 콧수염과 짧은 염소수염 | 겁먹은 표정, 50대 (노인 아님) |
| bok | 복 공공 | (2026-11-12 작가 지정) `_work/ref_input/bok_ref.webp`의 생김새 그대로: 수염 없는 둥글고 통통한 얼굴, 눈을 감고 활짝 웃는 초승달 눈, 둥근 볼, 회색 섞인 머리 | | | | 높은 검은 관모, 검붉은 비단 관복에 금빛 구름·새 자수 띠 |
| on | 온 숙비 | 긴 계란형 | 중간 크기, 가늘고 처진 눈꼬리, 회갈색 | 옅고 가늘게 | 작은 코, 얇은 입술 | 늘 내리깐 눈 |
| jeong | 정 덕비 | 갸름한 계란형, 부드러운 턱선 | 크고 맑은 검은 눈, 긴 속눈썹, 차분하게 살짝 내리뜬 눈빛 | 가늘고 곧게 | 작고 오똑한 코, 붉은 기 도는 작은 입술 | 단아하고 화려한 미인. 하 귀비보다 덜 화려하지만 4비답게 화려함. 점 없음 |
| baek | 백 현비 | 갸름한 역삼각 | 크고 짙은 쌍꺼풀, 연회색 | 가는 아치형 | 작고 오똑한 코, 핏기 없는 입술 | 창백함 |
| sohwa | 소화 장공주 (미혼: 머리를 반만 올리고 나머지는 내린다) | 광대가 살짝 있는 계란형 | 크고 치켜 올라간 고양이눈, 금색 | 진하고 각지게 | 작은 코, 도톰한 입술 | 한쪽 입꼬리만 올린 웃음 |
| soa | 임소아 | 갸름하고 부드러운 계란형 (통통하지 않게) | 크고 동그란 사슴눈, 갈색 | 둥글고 부드럽게 | 작은 코, 작은 입술 | 보조개, 마른 체형 |
| yeona | 연아 | 작은 하트형, 성인 얼굴 비율 | 중간 크기, 둥근 홑꺼풀, 짙은 갈색 | 짧은 일자 | 작은 코, 보통 입술 | 22세 성인. 아이 같은 비율 금지. 쌍상투 대신 뒤로 낮게 묶은 쪽머리에 연두 리본, 콧등에 아주 옅은 주근깨 |

얼굴 프롬프트에 넣는 영어 문장:

| 코드 | face features |
| --- | --- |
| sodam | looks like the emperor's younger half-brother (same straight nose bridge and similar slender face), but with a softer, smoother face line and gentler jaw, cat-like eyes: almond-shaped pale gold eyes with slightly upturned outer corners, opened a little wider than the emperor's, thinner softer eyebrows, calm neutral expression with soft gentle eyes, lips closed, no smile, no dimples |
| yukhan | square strong jaw, small deep-set grey eyes, thick straight dark eyebrows, straight high nose bridge, closed firm mouth, faint scar on the left cheek |
| ha | heart-shaped face with high cheekbones, medium almond-shaped amber eyes with long winged red eyeliner and a heavy-lidded haughty gaze, sharp arched eyebrows, straight refined nose, full red lips, a beauty mark under one eye |
| heo | man in his early 50s (not elderly, no white beard), long thin face with sunken cheeks, small nervous eyes with fine wrinkles, faint drooping eyebrows, long nose, thin moustache and a short goatee, anxious timid look |
| bok | clearly middle-aged palace eunuch, late 40s to 50, beardless round face, slightly plump with softly sagging cheeks, a few fine wrinkles at the eye corners and light smile lines around the mouth, narrow curved smiling eyes, faint rounded eyebrows, small nose, sly fawning smile, neat stylized webtoon supporting character (must look middle-aged, not young; not realistic, not elderly, not grotesque) |
| dan | elegant aristocratic woman in her early 40s (not old, not elderly), slender sharp long face with high cheekbones, long narrow black eyes with heavy-lidded composed gaze, thin long-drawn eyebrows, refined straight nose, thin neat lips, only very faint fine lines at the eye corners, slim tall figure, cold dignified beauty |
| on | long oval face, medium-size narrow grey-brown eyes with drooping outer corners, always looking slightly down, faint thin eyebrows, small nose, thin lips |
| jeong | beautiful elegant imperial consort in her late 20s, slender oval face with a soft delicate jawline, large clear black eyes with long lashes and a calm slightly lowered gaze, thin straight soft eyebrows, small refined nose, small rosy lips, serene graceful beauty, no moles, no beauty marks |
| baek | slender inverted-triangle face, large light grey eyes with deep double eyelids, thin arched eyebrows, small sharp nose, very pale almost colorless lips, pale skin |
| sohwa | oval face with slightly high cheekbones, large upturned cat-like gold eyes, bold angled eyebrows, small nose, full lips, one-sided smirk |
| soa | slim soft oval face with a slender jaw (not chubby, no full cheeks), large round doe-like brown eyes, soft rounded eyebrows, small nose, small lips, a dimple when smiling, slim slender body |
| yeona | adult woman of 22 with adult proportions (about seven heads tall, slender adult neck and shoulders, same height as the other women), small heart-shaped face with mature adult features, medium-size round single-lidded dark brown eyes, short straight eyebrows, small nose, medium lips, very faint freckles across the nose, earnest worried look, NOT childlike, NOT a little girl, no chibi proportions, no big head |

### 시트 프롬프트

| 코드 | 인물 | 시트 프롬프트 (그림체 블록 뒤에 붙임, 얼굴 → 몸 → 옷 순서) |
| --- | --- | --- |
| soyun | 황제 소윤 | (확정. 다시 만들지 않는다) young emperor, man in his late 20s, tall and lean, bored languid half-lidded dark gold eyes, black hair half tied up under a small gold crown, black imperial robe with gold dragon-cloud embroidery, jade belt. Main colors black and gold |
| sodam | 정친왕 소담 | face: man in his mid 20s who clearly resembles his older half-brother the emperor (same straight nose bridge, similar slender face) but with a softer smoother face line and gentler jaw, cat-like almond-shaped pale gold eyes with slightly upturned outer corners, opened a little wider, thinner softer eyebrows, no dimples, expression: calm neutral face with soft gentle eyes, lips gently closed, no smile, no teeth, man in his mid 20s, slimmer and shorter than the emperor, relaxed posture, pose: one hand holding a half-open folding fan near his chin, long straight silver hair tied loosely low at the nape with a plain ribbon (no crown, no tall hair ornament), pale blue silk robe with silver cloud embroidery, simple silver jade pendant. Main colors pale blue and silver |
| yukhan | 육 통령 육한 | face: square strong jaw, thick straight dark eyebrows, deep-set narrow grey eyes, straight nose, faint scar across the left cheek, slightly tanned skin, expression: stern unsmiling, mouth closed, man about 28, very broad shoulders and muscular build, the tallest of all, pose: standing at attention with one hand on the sword hilt, short deep indigo (dark blue-black) hair tied back in a small tight knot (no crown, no hairpin, no tassel), dark steel-grey lamellar armor with brass fittings over a dark grey robe, plain leather bracers. Main colors steel grey and brass, with deep indigo hair |
| dan | 태후 단씨 | face: elegant aristocratic woman in her early 40s (not old, not elderly, no sagging, no heavy wrinkles), slender sharp long face with high cheekbones, long narrow black eyes with a heavy-lidded composed gaze, thin long-drawn eyebrows, refined straight nose, thin neat lips, only very faint fine lines at the eye corners, expression: unreadable composed, slim and tall, pose: hands folded inside wide sleeves, glossy black hair with a single elegant silver streak in a refined high updo with a few gold and jade pins, luxurious layered aubergine-purple silk robe with gold-thread round coiled dragon medallions (small dragons curled inside circles) on the chest, shoulders and sleeves, not a large flowing dragon. Main color aubergine purple |
| wi | 황후 위씨 | face: woman in her early 30s, round gentle face, soft downturned kind eyes in warm brown, soft eyebrows, small mouth, expression: warm motherly smile, medium height, graceful, pose: holding a small round silk fan at her waist, black hair in a tall formal updo with a large gold phoenix crown and hanging pearl strings, deep crimson empress robe with gold phoenix embroidery. Main color crimson |
| ha | 하 귀비 | face: woman in her late 20s, sharp heart-shaped face with high cheekbones, upturned cat-like amber eyes with bold red eyeshadow, red lips, beauty mark under one eye, expression: haughty smirk, chin raised, tall and voluptuous but fully covered, pose: one hand on hip, other hand lifting the long sleeve, dark brown hair piled very high with many gold flower ornaments and dangling gold chains, rich gold and apricot robe. Main color gold |
| on | 온 숙비 | face: woman in her late 20s, quietly pretty refined face, long oval face, gentle grey-brown eyes usually lowered, soft thin eyebrows, small closed lips, expression: calm and reserved, slender graceful build, pose: standing with hands folded in front, slightly behind others, light brown hair in an elegant consort's updo with silver hairpins and small jade flowers, layered grey-green silk consort robe with fine silver embroidery and a pale inner layer, refined earrings — understated but clearly a high-ranking imperial consort, not plain, not poor. Main color grey-green |
| jeong | 정 덕비 | face: beautiful elegant imperial consort in her late 20s (about the same age as Noble Consort Ha), slender oval face with a soft delicate jawline, large clear black eyes with long lashes and a calm slightly lowered gaze, thin straight soft eyebrows, small refined nose, small rosy lips, no moles, no beauty marks, expression: serene faint smile, tall and slender, pose: holding prayer beads in both hands, glossy black hair in an elegant high consort's updo with jade and pearl plum-blossom hairpins and a few dangling pearl strands — ornate like a high-ranking consort but less flashy than Noble Consort Ha, layered blue-grey silk robe with silver and white plum-blossom embroidery and a white-jade inner collar. Main color blue-grey |
| baek | 백 현비 | face: woman about 30, delicate beautiful face, slightly thin, pale porcelain skin with a faint unwell pallor, light grey eyes that are tired but sharp and intelligent, very pale, almost colorless lips with only a faint hint of pink, a slightly bluish pallor around the eyes and lips, faintly flushed tired eyelids, expression: composed with a faint weary smile, slender fragile build but upright and dignified, pose: one hand resting lightly on her chest, black hair neatly arranged in a consort's updo with pearl and silver ornaments, layered white and pale silver silk consort robe with fine embroidery and a light shawl — an elegant imperial consort who is ill, not a ghost, not disheveled, no dark circles, no hollow cheeks. Main color white and silver |
| sohwa | 소화 장공주 | face: woman of 24, a grown adult (not a child, not a teenager), lively oval face with adult proportions, bright gold eyes with an upward sparkle, defined expressive eyebrows, red-tinted lips, expression: mischievous knowing grin, one eyebrow raised, average height, confident posture, pose: one hand holding a closed fan against her shoulder, black hair with a reddish tint in an unmarried princess half-up style: only the top section tied up with gold ornaments and small gold bells, the rest of the long hair hanging loose down her back (not a full updo), vermilion silk robe with gold trim, jeweled earrings. Main color vermilion |
| soa | 임소아 (임 재인) | face: woman of 22, a grown adult (not a child, not a teenager), slim soft oval face with a slender jaw (not chubby, no full cheeks) and adult proportions, warm round brown eyes, soft eyebrows, light rosy cheeks, expression: sweet friendly smile, average height, slim and slender (not plump), pose: holding the end of her sleeve with both hands, brown hair in an elegant low-rank consort's updo with small pink flowers and a simple silver hairpin (no childish braids, no crown), pale pink silk robe with light embroidery — modest because she is the lowest rank, but clearly a palace consort. Main color pale pink |
| heo | 허 어의 | face: man in his 50s, thin long face, sunken cheeks, small nervous eyes with wrinkles, thin moustache and short goatee, expression: anxious and timid, thin bony build, slightly stooped, pose: clutching a small wooden medicine box to his chest, half-grey hair in a topknot under a black physician's cap, deep navy physician's robe. Main color deep navy |
| bok | 복 공공 | face: clearly middle-aged palace eunuch, late 40s to 50, beardless round face, slightly plump with softly sagging cheeks, a few fine wrinkles at the eye corners and light smile lines, narrow curved smiling eyes, expression: sly fawning smile, stylized webtoon supporting character (not realistic, not elderly, not grotesque), short build, pose: bowing slightly with a horsetail whisk over one arm, dark red eunuch robe and black eunuch hat. Main color dark red |
| yeona | 연아 (시녀) | face: adult woman of 22 with adult proportions (about seven heads tall, slender adult neck and shoulders, same height as the other women, not childlike, not a little girl, no big head), small heart-shaped face with adult proportions, round dark eyes, a few faint freckles on the nose, expression: earnest worried look, average height, slim, pose: standing with a tea tray held in both hands, brown hair in a single neat low bun at the back tied with a light green ribbon (no twin buns, no jewels), simple light green palace maid's robe with a white sash, plainer than the consorts. Main color light green |

---

## 5. 인물 `c/코드/번호.webp`

템플릿: 그림체 블록 + `bust-up close-up portrait from the chest up, 4:3 landscape, [인물 설명 요약], [표정]` + 해당 `ref/` 시트 첨부


### 만드는 방법 (2026-11-16 확정 — 옷 색·무늬가 흔들려서 바꿈)
- 시트·ha_face·장소 그림 세 장을 함께 첨부했더니 ha_face의 금빛 모란 옷과 장소의 붉은 금빛이 인물 옷에 섞였다. 그래서:
  1. **1번(기본)만 먼저**: 첨부는 그 인물의 `ref/코드_sheet.webp` **한 장만**. ha_face와 장소 그림은 첨부하지 않는다. 배경은 아래 표의 장소를 **글로만** 적는다.
     - 프롬프트 맨 앞: `Draw the person in the attached reference sheet. Copy the outfit colors, fabric pattern, embroidery, hair and ornaments exactly from the sheet. Do not change any outfit color or pattern.`
  2. 1번을 시트와 나란히 놓고 옷 색, 무늬, 장신구, 머리가 같은지 확인. 다르면 1번만 다시.
  3. **나머지 번호는 1번을 고쳐서**: 첨부는 `c/코드/1.webp` 한 장. `Edit the attached image. Keep everything exactly the same — outfit, colors, embroidery, hair, ornaments, background, framing and size. Change only the facial expression to: [표정 문장].`
  4. 9번 특수처럼 손이나 자세가 바뀌는 장도 1번을 고쳐서 만든다(옷과 배경 유지).
- 소윤 침소 버전(10~13)은 따로: 10번을 시트 한 장 첨부로 먼저 만들고, 11~13번은 10번을 고쳐서.

### 배경 (2026-11-16 확정: 자기 거처를 흐리게)
- 인물마다 가장 자주 있는 장소를 **글로 적어** 배경으로 **아주 흐리게(강한 아웃포커스)** 깐다. 장소 그림은 첨부하지 않는다(색이 옷에 섞임). 인물이 주인공이고 배경은 분위기만.
  | 인물 | 배경 |
  | --- | --- |
  | soyun | p/16 대전 |
  | sodam, sohwa | p/6 어화원 |
  | yukhan, bok | p/13 밤의 긴 회랑 |
  | dan | p/7 태후전 |
  | wi | p/8 황후전 |
  | ha | p/9 귀비전 |
  | on, jeong | p/5 비의 전각 |
  | baek | p/15 현비의 병실 |
  | soa, yeona | p/2 재인의 처소 |
  | heo | p/11 어의원 |
- 같은 인물의 표정은 모두 같은 배경, 같은 흐림 정도로 맞춘다.

### 표정 번호

| 번호 | 표정 | 프롬프트 |
| --- | --- | --- |
| 1 | 기본 | calm neutral expression |
| 2 | 미소 | slight restrained smile |
| 3 | 화남 | cold anger, narrowed eyes |
| 4 | 슬픔 | quiet sorrow, lowered eyes |
| 5 | 놀람 | surprised, eyes widened |
| 6 | 의심 | suspicious sidelong glance |
| 7 | 진지 | serious, firm gaze |
| 8 | 어이없음 | comedic exaggerated dumbfounded face, chibi-like gag expression |
| 9 | 특수 | 아래 인물별 |

### 9번 (특수)
- soyun 9: rare genuine soft smile, the boredom gone from his eyes
- sodam 9: fan lowered, smile gone, cold calculating true face
- yukhan 9: reaching out to block a teacup, protective, tense

### 특수 번호 (조연)
- soa 6은 **배신 뒤**의 얼굴이다: same sweet smile but cold jealous eyes
- baek 1은 병상에 기댄 모습: leaning on a pillow in bed, pale and weak


### 소윤 침소 버전 (2026-11-16 추가) `c/soyun/10~14.webp`
- 배경: p/14 황상의 침전 (흐리게). 밤, 등롱 불빛.
- 옷: 흰색·아이보리 비단 **잠옷(속옷 겉옷)**, 앞섶을 **단정하게 끝까지 여민다**. 가슴·쇄골 노출 금지 (`plain white silk sleeping robe, collar fully closed, no exposed chest, no exposed collarbone`).
- 머리: 금관을 벗고 흑발을 **풀어 내린** 모습. 장신구 없음.
- 분위기는 나른하고 사적인 느낌이되 선정적이지 않게.
  | 번호 | 표정 |
  | --- | --- |
  | 10 | 나른한 기본 얼굴, 반쯤 감긴 눈 (relaxed drowsy expression, half-lidded eyes) |
  | 11 | 옅은 미소 (faint private smile) |
  | 12 | 떠보는 눈빛, 고개를 살짝 기울임 (teasing probing gaze, head slightly tilted) |
  | 13 | 진심이 비치는 부드러운 얼굴 (soft sincere look, the boredom gone) |

#### 14번 (2026-11-16 추가, 침소 버전의 예외 한 장) `c/soyun/14.webp`
- 장면: 주인공이 침대에 **반듯이 누워 천장을 올려다보는** 시점. 소윤은 그 위에 **엎드려** 몸을 겹치듯 숙이고 **얼굴을 정면 아래로(카메라 쪽으로)** 내려다본다. 소윤이 누워 있는 것처럼 보이면 실패. 주인공은 그리지 않는다.
- 구도: 카메라는 소윤 **바로 아래**에서 위를 본다. 소윤 머리 뒤로 **침대 닫집(천장 휘장)**이 보여야 위아래가 분명해진다. 풀어 내린 흑발이 **카메라 쪽으로 곧장 늘어진다**. 두 팔을 **쭉 편 채** 손바닥을 주인공 머리 양옆 침대에 짚고 몸을 받친다(팔꿈치 굽힘 금지). 두 팔이 화면 양옆에서 소윤 어깨까지 곧게 뻗어 얼굴을 감싸는 틀이 된다.
- 옷: 10번과 같은 흰 비단 잠옷. 허리끈이 느슨해 **앞섶이 비스듬히 벌어지고, 깃이 한쪽 어깨에서 위팔 쪽으로 자연스럽게 흘러내려** 그쪽 어깨와 쇄골이 드러난다. 천은 주름지며 늘어지고, 반대쪽 어깨는 걸쳐 있다. 옷에 구멍이 뚫린 것처럼 어깨만 드러나면 실패. 가슴 노출이나 강조는 없게. 이 한 장만 "앞섶 끝까지 여밈" 규칙의 예외.
- 표정: 덮치려는 듯 짙고 집요한 눈빛, 입꼬리만 살짝, **볼은 발그레하게**.
- 만드는 법: 자세가 크게 바뀌므로 10번을 고치지 않고 **새로** 그린다. 첨부는 `ref/soyun_sheet.webp` + `c/soyun/10.webp`(같은 인물이라 허용) 두 장.
- 영어: `Camera pointing perfectly straight up from directly below (90-degree vertical view, no side angle). The viewer is lying flat on their back on a bed, looking up at the ceiling. The young emperor is lying prone on top of the viewer, his body pressed close above, holding himself up with both arms fully straight and locked, palms pressed on the bed on either side of the viewer's head (elbows NOT bent), the two straight arms rising from the sides of the frame up to his shoulders and framing his face, his face pointing straight down toward the camera, looking down into the viewer's eyes. Behind his head we see the bed canopy and ceiling drapes, making it clear he is above. His long loose black hair hangs straight down toward the camera, framing his face. His face looks down from above, framed between his straight arms. Same plain white silk sleeping robe as the attached image, loosely tied: the cross collar has loosened and opened in a natural diagonal, and on one side the whole collar edge has slid off his shoulder down onto his upper arm in soft draped folds, revealing that shoulder and collarbone; the other side still rests on his shoulder. The fabric hangs naturally with gravity, not a cut-out. No focus on the chest. Cheeks flushed pink, intense possessive gaze, slight smirk, as if about to lean down. He is NOT lying down. Dim lantern light. The viewer is not shown at all. Tasteful, not explicit, no nudity.`

### 장수

| 인물 | 번호 | 장수 |
| --- | --- | --- |
| soyun, sodam, yukhan | 1~9 | 각 9 (27) |
| soyun 침소 버전 | 10~14 | 5 |
| dan, wi, ha, on, jeong, baek, sohwa, soa | 1, 2, 3, 5, 6, 7 | 각 6 (48) |
| heo, bok, yeona | 1, 2, 5, 8 | 각 4 (12) |

인물 합계 92장.

---

## 6. 프롤로그 `pro/` (크랙 미디어에 '프롤로그'로 등록, 16:9)

| 파일 | 크랙 태그 | 내용 |
| --- | --- | --- |
| `pro/1.webp` | 담장 | 끝없이 이어진 붉은 궁 담장 사이 길, 두 젊은 후궁의 뒷모습 (하나는 꽃장식으로 틀어 올린 갈색 머리) |
| `pro/2.webp` | 행렬 | 엎드린 궁인들 사이로 지나가는 황상의 행렬, 금관 쓴 황제의 옆모습, 곁에서 고개를 살짝 돌린 짙은 쪽빛 머리의 무관(육한) |
| `pro/3.webp` | 처소 | 후궁전 끝 햇빛이 반만 드는 작고 낡은 처소, 짐을 풀다 만 상자 |
| `pro/4.webp` | 찻잔 | 해 질 무렵 탁자 위 꽃 향이 피어오르는 백자 찻잔 하나, 그 위로 숙인 시녀 연아의 놀란 얼굴 |

## 7. 상세 설명 `d/` (크랙 미디어에 '상세'로 등록, 2:3 세로)

| 파일 | 크랙 태그 | 내용 |
| --- | --- | --- |
| `d/1.webp` | 표지 | 붉은 궁문 앞, 화려한 후궁 복식을 입은 주인공의 뒷모습. 한 손에 찻잔 |
| `d/2.webp` | 찻잔 | 검은 칠 탁자 위 김이 오르는 찻잔, 잔 옆에 놓인 은비녀 |
| `d/3.webp` | 세남자 | 황제 소윤, 정친왕 소담, 육 통령 육한이 각자 다른 방향을 보고 선 구도 |
| `d/4.webp` | 후궁들 | 2열×3행 6분할 상반신 얼굴 모음, 품계 순서(왼쪽 위부터): 위 황후 → 하 귀비 → 온 숙비 → 정 덕비 → 백 현비 → 임소아. **새로 그리지 않고 확정된 `c/코드/1.webp`를 잘라 합친다**(얼굴·옷이 표정 그림과 똑같게). 칸 사이는 얇은 금빛 선, 글자 없음 |
| `d/5.webp` | 독잔 | 엎어진 찻잔과 흩어진 협죽도 꽃잎, 그 앞에 선 주인공의 치맛자락 |

---

## 7-1. 썸네일 `thumb/` (2026-11-17 확정: A안 "독잔을 내미는 소윤")

- 소윤이 정면을 보며 받침 없는 백자 찻잔을 독자 쪽으로 내민다. 입꼬리만 살짝, 무심하고 위험한 눈빛. 찻잔 위 옅은 김, 아래쪽에 협죽도 꽃잎 몇 장.
- 옷·얼굴·흑발·금관은 시트 그대로. 배경은 흐린 대전의 붉은 기둥과 금빛, 어두운 쪽으로.
- 크랙 썸네일 비율은 확인 불가 → 2:3 세로로 만들되 얼굴과 찻잔을 가운데에 모아 **정사각형으로 잘라도** 둘 다 들어가게.
- 검열 대상: 노출·글자·피·독을 직접 보여 주는 표현 금지.

---

## 7-2. 포스터 `poster/` (2026-11-17: 크랙 작품 화면 안, thumb/3 기준, 제목 넣음)

- 바탕: `thumb/3.webp`. 소윤의 얼굴·머리(지금의 보랏빛 흑발 그대로, 작가 결정)·옷·찻잔은 **그대로 두고** 화면을 넓혀 포스터 구도로 만든다.
- 제목 「후궁에 들어갔더니 매일 독을 마신다」는 **AI로 그리지 않고 코드로 얹는다**(AI는 한글을 깨뜨림). 그림 단계에서는 제목 들어갈 자리를 비워 둔다.
- 크랙 포스터 칸의 비율은 확인 불가 → 2:3 세로로 만들고, 작가가 비율을 확인하면 다시 자른다.
- 검열 대상: 노출·피·독을 직접 보여 주는 표현 금지.

---

## 8. 장소 `p/` (16:9, 인물 없이 또는 아주 작게) — 29장. 같은 궁이라 기와·담장 색과 시대 느낌을 모두 맞춘다. 23~26은 p/6 어화원과 같은 구도의 계절 변형.

| 번호 | 장소 |
| --- | --- |
| 1 | 황궁 정문과 붉은 담장 |
| 2 | 재인의 처소 (후궁전 끝, 작고 낡음) |
| 3 | 첩여의 처소 (조금 넓어짐) |
| 4 | 빈의 처소 (정원이 딸린 전각) |
| 5 | 비의 전각 (금빛 장식) |
| 6 | 어화원 (후원, 연못과 협죽도 꽃밭) |
| 7 | 태후전 (보랏빛 휘장, 향로) |
| 8 | 황후전 (봉황 장식, 붉은 휘장) |
| 9 | 귀비전 (금빛 화려함) |
| 10 | 연회장 (등롱과 긴 상) |
| 11 | 어의원 (약재 서랍장) |
| 12 | 냉궁 (낡고 버려진 전각, 마른 덩굴) |
| 13 | 밤의 긴 회랑 (등롱, 순찰 무관의 그림자) |
| 14 | 황상의 침전 (안쪽, 사람 없이. 넓은 침상은 휘장에 가려 멀리, 등롱과 향로, 차분하고 위엄 있게. 선정적인 분위기 금지) |
| 15 | 백 현비의 병실 (약 냄새, 닫힌 창) |
| 16 | 대전 (황제가 조회를 여는 정전. 높은 계단 위 용상, 붉은 기둥, 금빛 장식, 양옆으로 늘어선 빈 신하 자리) |
| 17 | 장공주의 처소 (벚꽃 장식, 밝고 화사한 전각, 소문을 사고파는 찻자리) |
| 18 | 태감 처소 (황상을 모시는 차례를 정하는 곳. 후궁 이름패를 올려 둔 쟁반, 장부가 쌓인 책상. 패와 장부에 글자 없음) |
| 19 | 궁 감옥·심문실 (어둡고 차가운 돌방, 쇠창살, 등잔 하나. 고문 도구나 피는 그리지 않는다) |
| 20 | 궁녀 처소와 우물가 (빨래 바구니, 좁은 마당, 수군대기 좋은 구석) |
| 21 | 연못가 정자 (밤, 등롱 몇 개, 연못에 비친 달. 몰래 만나는 곳) |
| 22 | 궁 뒷문과 궁 밖 길 (새벽 안개, 작은 쪽문, 멀리 이어지는 길) |
| 23 | 어화원 봄 (벚꽃과 복숭아꽃, 연둣빛) |
| 24 | 어화원 여름 (연꽃이 핀 연못, 짙은 초록) |
| 25 | 어화원 가을 (단풍과 국화, 떨어진 잎) |
| 26 | 어화원 겨울 (눈 덮인 정원, 매화, 얼어붙은 연못) |
| 27 | 불당 (향 연기, 작은 불상, 방석. 정 덕비가 기도하고 태후와 차를 마시는 곳) |
| 28 | 산실 (출산하는 방. 두꺼운 휘장, 따뜻한 등불, 약탕기. 사람과 출산 장면은 그리지 않는다) |
| 29 | 목욕간 (황상을 모시기 전 몸을 씻는 곳. 김이 오르는 나무 욕조, 떠 있는 꽃잎, 향로, 반쯤 걷힌 휘장, 놓인 비단 옷. **사람은 절대 그리지 않는다**) |

## 9. 상황 `s/` (16:9, 자주 반복되는 장면. 주인공은 뒷모습·손만)

| 번호 | 상황 |
| --- | --- |
| 1 | 독이 든 찻잔을 앞에 둔 탁자 |
| 2 | 웃전에 문안 인사 (엎드린 후궁들) |
| 3 | 연회 술자리 |
| 4 | 진맥 (내민 손목과 어의의 손) |
| 5 | 소매 아래로 은 주머니를 건넴 |
| 6 | 회랑에서 수군대는 궁녀들 |
| 7 | 교지 낭독 (태감이 펼친 빈 두루마리) |
| 8 | 앓아누운 병상 (흐트러진 이불, 약사발) |
| 9 | 밤에 등롱을 앞세운 가마 |
| 10 | 은비녀로 음식을 살핌 |

## 9-1. 이벤트 `e/` (16:9, 고정 사건과 결말. 한 장씩 공들여 만든다)

공통: 주인공은 뒷모습·실루엣·손만(예외: 8번은 부채로 얼굴 전체를 가린 앞모습). 품계 교지(2, 25, 26)에는 **주인공을 그리지 않는다.** 화면에는 교지를 펼쳐 읽는 복 공공(가운데, 얼굴이 보이게 두루마리는 가슴 높이), 뒤의 궁인, 앞쪽에 놓인 하사품만. 품계가 오를수록 배경 전각이 커지고, 궁인이 늘고, 하사품이 화려해진다. 교지에는 글자를 그리지 않는다. 죽음·처형·아이를 잃는 장면은 직접 그리지 않고 빈 자리, 엎어진 물건, 그림자로 보여 준다. 회임·출산은 몸을 그리지 않고 진맥하는 손목, 산실 문밖, 강보로만 보여 준다(11, 12, 27, 29).

### 만드는 방법 (2026-11-17 확정)
- 첨부: 배경 `p/` 한 장(있으면) + 얼굴이 나오는 인물의 `ref/코드_sheet.webp`(최대 2장). ha_face, 나오지 않는 인물 그림은 첨부하지 않는다.
- **배경은 반드시 중국풍 황궁**(한국 궁궐 기와·단청 금지). p/ 그림은 **분위기·건축 양식을 맞추는 참고**일 뿐이다(작가 결정 2026-11-17). 장면에 맞게 각도·거리·시간대가 다른 배경을 **새로 그려도 된다.** p/ 와 같은 장소라면 기와·기둥·담장 색과 양식만 맞춘다. 첨부는 구도에 도움이 될 때만. 인물 시트는 두 번째부터. 배경 색이 인물 옷에 섞이지 않았는지 꼭 확인.
- 프롬프트 맨 앞(인물이 있을 때): `Use the attached reference sheets only for each person's face, hair, outfit colors and embroidery. Copy them exactly. Do not mix colors between people.`
- 그다음 2번 칸 스타일 블록, 그다음 장면 문장.
- 주인공: 얼굴을 절대 그리지 않는다. 뒷모습·손·소매만. 옷은 수수한 쪽빛 회청색 교차 깃 비단옷, 품계가 높을수록 금자수가 늘어난다.
- 궁인·내관 같은 엑스트라는 얼굴을 작고 흐리게.
- 크기는 p/ 그림과 같은 16:9, 그림 안 글자 금지.

| 번호 | 사건 | 구도 |
| --- | --- | --- |
| 1 | 첫 찻잔 | 해 질 무렵 처소, 찻잔을 든 주인공의 손 |
| 2 | 첩여 교지 | 배경 p/2 재인 처소 마당. 교지를 읽는 복 공공, 뒤에 내관 둘. 앞에 작은 쟁반 하나(비단 한 필, 옥비녀) |
| 3 | 소아의 배신 | 찻잔을 건네며 웃는 임소아, 차가운 눈. 찻잔은 받침 없는 하얀 백자 찻잔(서양식 컵·받침 금지) |
| 4 | 빈 처소로 옮김 | 배경 p/4. 새 전각 문으로 들어가는 주인공 뒷모습과 함을 든 궁인 행렬(화면 가운데). 화면 구석 멀리 회랑 기둥 뒤에서 작게 지켜보는 임소아 |
| 5 | 숙비 처소 수색 | 열린 함 속 빈 서찰 다발 |
| 6 | 현비의 독을 알아챔 | 병상의 백 현비와 약사발, 사발에 가까이 댄 주인공의 손 |
| 7 | 현비를 살림 | 창이 열린 병실, 기운을 찾은 백 현비 |
| 8 | 비 책봉 | 배경 p/5 비의 전각 안. 화려한 의자에 정면으로 단정히 앉은 주인공. **둥근 비단 부채(단선)로 얼굴 전체를 가린다**(눈·코·입 모두 안 보임, 부채 위로 머리 장식만 보임). 옷은 쪽빛 회청색 교차 깃에 금실 자수가 가장 화려하게, 금 비녀와 보석 장식이 많은 높은 올림머리 |
| 9 | 황후의 몰락 | 바닥에 떨어진 봉황 비녀 |
| 10 | 황후 즉위 | 봉황 관을 쓴 주인공의 뒷모습, 엎드린 궁인들 |
| 11 | 공주 출산 | 분홍 강보에 싸인 아기 (얼굴 작게) |
| 12 | 황자 출산 | 금빛 강보, 기뻐하는 황상 |
| 13 | 아이를 잃음 | 빈 요람과 떨어진 작은 신발 한 짝 |
| 14 | 냉궁 유폐 | 냉궁 문이 닫히는 모습, 문틈의 빛 |
| 15 | 반역 결행 | 빈 용상 위로 길게 드리운 두 그림자 |
| 16 | 새 황제 즉위 | 즉위식 행렬. 중국풍 황궁 정전 앞 넓은 돌마당(글로, 한국 궁궐 금지). 가운데 길을 따라 카메라 쪽으로 걸어오는 정친왕(정면, 얼굴·은발은 시트). 당나라식 면복: 검은 윗옷, 진홍 아랫단, 금실 용 자수, 흰 속깃, 넓은 소매, 큰 띠, 두 손에 흰 옥 홀. 머리에 앞뒤로 구슬 줄이 늘어진 면류관(구슬 사이로 얼굴이 비침). 뒤에 큰 의장 부채와 깃발, 양옆에 진홍 관복 신하들이 줄지어 허리 숙여 절함. 맑은 하늘, 주인공 없음. 작가 참고: 즉위식 행렬 사진(구도·분위기만) |
| 17 | 도주 | 새벽 궁문 밖, 말 위의 두 사람 뒷모습 (육한: 짙은 쪽빛 머리) |
| 18 | 처형 | 비 내리는 마당에 떨어진 비녀와 빈 자리 |
| 19 | 소윤 첫 만남 | 행렬 속 가마 발이 걷히고 소윤이 고개를 돌려 정면을 봄. 앞쪽에 엎드린 주인공의 뒷모습(머리와 어깨만) |
| 20 | 소윤의 마음 | 밤 침전 창가, 주인공의 손을 잡은 소윤. 주인공은 손과 소매만, 소윤은 지루함이 사라진 진심 어린 얼굴 |
| 21 | 육한이 구함 | 주인공 앞을 막아선 육한의 뒷모습과 뽑힌 검, 주인공은 그 뒤 소매만 |
| 22 | 육한 밤 회랑 | 등롱 하나 켜진 어두운 회랑, 기둥 그늘에서 주인공을 내려다보는 육한. 주인공은 어깨 뒷모습만 |
| 23 | 소담 어화원 | 꽃이 지는 어화원, 접부채를 반쯤 접으며 다가오는 소담. 주인공은 뒷모습만 |
| 24 | 소담의 반역 제안 | 촛불 하나 켜진 어두운 정자, 탁자 위에 펼친 빈 지도와 부채, 낮게 웃는 소담. 주인공은 손만 |
| 25 | 빈 교지 | 배경 p/3 첩여 처소 마당. 교지를 읽는 복 공공, 뒤에 내관·궁녀 여섯쯤. 앞에 옻칠 함 몇 개, 비단 여러 필, 은 쟁반 |
| 26 | 비 교지 | 배경 p/4 빈 처소 전각 앞뜰. 황금빛 교지를 펼친 복 공공, 양쪽에 줄지어 선 궁인 여럿. 앞에 금테 두른 함이 줄지어 놓이고 금 장신구, 관을 담은 함 |
| 27 | 회임 진맥 | 휘장 아래로 내민 주인공의 손목, 손끝을 댄 채 놀라 눈이 커진 허 어의. 배나 몸은 그리지 않는다 |
| 28 | (삭제: 회임 소식, 2026-11-17 작가 결정. 번호는 비워 둔다) | — |
| 29 | 산실 문밖 | 밤, 두꺼운 휘장이 내려진 산실 문 앞에서 서성이는 소윤의 옆모습, 문틈의 등불. 산실 안은 그리지 않는다 |

## 10. 소품 `i/` (16:9, 소품은 가운데에 작게, 단색 배경)

| 번호 | 소품 |
| --- | --- |
| 1 | 백자 찻잔 |
| 2 | 은비녀 |
| 3 | 향낭 (사향) |
| 4 | 탕약 사발 (홍화) |
| 5 | 은 주머니 |
| 6 | 교지 두루마리 (글자 없음) |
| 7 | 봉인된 서찰 (글자 없음) |
| 8 | 장부 (글자 없음) |
| 9 | 협죽도 꽃가지 |
| 10 | 정친왕의 접부채 |
| 11 | 붉은 끈을 감은 육 통령의 검 |
| 12 | 황후의 봉황 비녀 |
| 13 | 약재 상자 |

---

## 합계

| 폴더 | 장수 |
| --- | --- |
| ref | 14 |
| c | 92 |
| pro | 4 |
| d | 5 |
| p | 29 |
| s | 10 |
| e | 28 |
| i | 13 |
| **합계** | **195** (ref 포함) |
