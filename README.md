# BloomTrip — AI 브랜드 광고 스토리보드 (사후 · 실제 진행)

기획 단계 스토리보드를 실제 제작 진행 결과에 맞춰 수정한 사후 기록본입니다.

- **프로젝트명**: BloomTrip 시니어 여행 브랜드 광고
- **최종 결과물**: 10초 내외 광고 영상 1편 (MP4)
- **제작 도구**: GPT Image · OpenAI Sora 2 · Suno · ElevenLabs · CapCut

---

## 1. 브랜드 아이덴티티

| 항목 | 내용 |
|---|---|
| 브랜드명 | BloomTrip (블룸트립) |
| 브랜드 컨셉 | 시니어를 위한 프리미엄 여행 브랜드. "인생의 두 번째 전성기"를 다시 꽃피운다는 의미를 담음 |
| 타겟 | 시니어 커플 및 시니어 그룹(동창·동호회 등 단체 여행객) |
| USP(차별점) | 프리미엄 경험(고급 숙소·소규모 투어) + 버킷리스트 실현(평생 가고 싶었던 여행지) |
| 톤앤매너 | 에너지: 잔잔한 역동 / 색감: 선명한 비비드 / 카피: 짧고 강한 선언형 |

> 한 줄 정의: *"여유롭지만 강렬하게, 인생의 전성기를 선명하게 담는다"*
> 느린 카메라 워크와 여유로운 컷 전환 위에, 파란 바다·원색 계열의 높은 채도 색감을 얹고, 짧고 단정적인 카피로 감정을 확 잡아당기는 방식으로 표현.

## 2. 캠페인 목표 / 핵심 메시지

| 항목 | 내용 |
|---|---|
| 광고 목적 | 감성 공감 → 시니어 세대의 여행 욕구 자극 |
| 핵심 메시지(한 문장) | **"당신의 두 번째 전성기, BloomTrip과 함께 다시 피어나세요."** |
| 스토리 구조 | 기승전결형 — 여러 여행지를 거치는 여정(기·승) → 설산 정상에서의 도달(전) → 발자국이 꽃으로 개화하며 브랜드 메시지로 수렴(결) |
| 브랜드 인지 장치(마지막 구간) | Scene 4(엔딩)에 로고 "BloomTrip" + 동일 문구의 내레이션·자막 카피를 동시 배치하여 CTA 기능 수행 |

## 3. 사용 도구 목록 (실제 진행 기준)

| 구분 | 도구 | 사용 목적 | 비고 |
|---|---|---|---|
| 이미지 생성 | GPT Image | 씬별 키비주얼(참고 이미지) 생성, Scene 4 로고·부케 이미지 생성 | 기획 단계와 동일 |
| 비디오 생성 | OpenAI Sora 2 | Image-to-Video 방식으로 확정된 키비주얼을 모션 영상으로 변환 | 기획 단계와 동일 |
| 오디오(배경음악) 생성 | **Suno** | 영상 전체에 삽입되는 배경음악(BGM) 생성 | **변경됨** — 최초 계획엔 별도 배경음악 도구 미지정 |
| 나레이션 생성 | **ElevenLabs** | Scene 4 나레이션("당신의 두 번째 전성기…") 음성 합성 | **변경됨** (기존: GPT-4o mini TTS) |
| 통합 편집 | **CapCut** | 씬 연결, 컷 편집, 한글 카피 자막 합성, BGM/오디오 레벨 조정 | **확정됨** (기존: 택1 미확정) |

> 이미지 생성 단계에서 스토리보드를 최대한 확정한 뒤 Sora 2로 영상 변환을 진행하는 방식으로, 영상 생성 크레딧 소모를 최소화하는 전략을 취함.

## 4. 변경 이력 (기획 대비 실제 진행)

| 항목 | 기획 당시 | 실제 진행 |
|---|---|---|
| 나레이션 생성 | GPT-4o mini TTS | ElevenLabs |
| 배경음악(오디오) 생성 | 미지정 | Suno |
| 통합 편집 툴 | CapCut/Premiere Pro/DaVinci Resolve 중 택1(미확정) | CapCut로 확정 |

**변경 사유**: 기존에 사용하려던 OpenAI 계열 네이티브 오디오 생성 프로그램(GPT-4o mini TTS)의 토큰(크레딧)이 부족해져, 나레이션은 ElevenLabs로, 배경음악은 Suno로 도구를 변경하여 진행함. 통합 편집 툴은 실제 작업 과정에서 CapCut으로 확정됨.

## 5. 씬 구성(콘티)

| 씬 | 내용 | 길이 |
|---|---|---|
| Scene 1-A | 유럽(프라하풍 골목) — 인물 말단(다리) 등장 | 1.5초 |
| Scene 1-B | 지중해(산토리니풍) — 인물 등장 | 1.5초 |
| Scene 1-C | 남미(마추픽추) — 인물 등장 | 1.5초 |
| Scene 1-D | 알프스 — 인물 등장 | 1.5초 |
| Scene 2 | 알프스 설산 초입 — 시니어 4인 풀샷, 발자국 노출 | 2초 |
| Scene 3 | 발자국 → 꽃 개화 | 1.5초 |
| Scene 4 | 브랜드 로고 + 카피 + 나레이션 | 2초 |
| **합계** | | **11.5초** |

> 미션 권장 스펙은 "10초 이내"이나, 서사 완성도(4개 여행지 몽타주 + 클라이맥스 + 엔딩)를 위해 팀 내부적으로 10초 내외(±1.5초) 허용 범위로 조정하여 진행. 최종 출력 파일은 약 11.98초.

### Scene 1-A · 유럽 (1.5초)
- **목표 메시지**: 여정의 시작 — 첫 발걸음으로 브랜드의 여행 세계관을 연다
- **화면 구성**: 프라하풍 유럽 골목(컬러풀한 건물, 자갈길), 골든아워 조명, 저앵글. 시니어의 다리·발이 화면 하단에서 걸어 들어오며 등장. 텍스트 없음.
- **내레이션/카피**: 없음(비주얼 오프닝)
- **사용 도구**: GPT Image(키비주얼 생성) → Sora 2(모션 변환, Image-to-Video)
- **입력 프롬프트**:
  ```
  A cinematic wide shot of a European cobblestone street with colorful buildings (Prague style), golden hour lighting.
  A senior person's lower legs and feet ONLY (below the knee) walking into frame from the bottom, wearing comfortable travel shoes.
  Do NOT show upper body, torso, or above the knee.
  Warm, vivid colors. Landscape 16:9 ratio, 1920x1080. Photorealistic.
  ```
- **출력 결과 요약**: 프라하 골목 배경과 골든아워 색감은 의도대로 확보. 다리 노출 범위가 완전히 무릎 아래로 절제되지는 않았으나, 배경 퀄리티를 우선하여 해당 결과로 확정.
- **결과 파일명**: `scene1a_keyvisual.png` / `scene1a_motion.mp4`

**🔁 프롬프트 수정 전/후**
- **수정 전**: "A senior person's legs and feet slowly walking into frame from the bottom, wearing comfortable travel shoes." (신체 노출 범위 지정 없음, 비율 지정 없음) — 인물 상반신까지 과도하게 노출되어 배경 중심의 브랜드 톤과 불일치, 비율도 16:9와 불일치.
- **수정 후**: "…lower legs and feet ONLY (below the knee)… Do NOT show upper body, torso, or above the knee… Landscape 16:9 ratio, 1920x1080." — 배경(여행지)이 화면의 주인공이 되도록 인물 노출을 제한하고, 해상도·비율을 명시함.

### Scene 1-B · 지중해 (1.5초)
- **목표 메시지**: 여정의 확장 — 두 번째 여행지로 세계관을 넓힌다
- **화면 구성**: 산토리니풍 흰색 건물과 블루 돔, 비비드한 파란 바다/하늘. 인물은 화면 오른쪽 1/3 지점에 작게 배치되어 배경이 주인공이 되도록 구성.
- **사용 도구**: GPT Image → Sora 2
- **입력 프롬프트**:
  ```
  A cinematic wide shot of a Mediterranean coastal scene, white-washed buildings with blue domes (Santorini style), bright vivid blue sea and sky in background.
  A senior person's lower legs and feet ONLY (below the knee) positioned on the RIGHT SIDE of the frame, taking up only about 20-25% of the total frame width. The person is SMALL relative to the background. Walking shoes and socks visible.
  The LEFT SIDE and CENTER of the frame shows the full Santorini landscape clearly.
  Camera angle is low, near ground level. Rule of thirds composition — subject on right third.
  Warm, vivid saturated colors. Landscape 16:9 ratio, 1920x1080. Photorealistic.
  ```
- **출력 결과 요약**: 산토리니 배경이 넓게 살아있고 인물은 보조 요소로 축소 배치되어 의도대로 확정.
- **결과 파일명**: `scene1b_keyvisual.png` / `scene1b_motion.mp4`

### Scene 1-C · 남미 (1.5초)
- **목표 메시지**: 여정의 확장 — 세 번째 여행지, 이국적 세계관 확장
- **화면 구성**: 마추픽추 유적과 녹색 산악 지형, 인물은 화면 오른쪽에 작게 배치(1-B 구도 계승).
- **사용 도구**: GPT Image → Sora 2
- **입력 프롬프트**:
  ```
  A cinematic wide shot of a South American landscape, colorful colonial buildings or Machu Picchu ruins in background, lush green mountains and dramatic sky.
  A senior person's lower legs and feet ONLY (below the knee) positioned on the RIGHT SIDE of the frame, taking up only about 20-25% of the total frame width. The person is SMALL relative to the background. Walking shoes and socks visible.
  The LEFT SIDE and CENTER of the frame shows the full South American landscape clearly.
  Camera angle is low, near ground level. Rule of thirds composition — subject on right third.
  Rich vivid colors, dramatic lighting. Landscape 16:9 ratio, 1920x1080. Photorealistic.
  ```
- **출력 결과 요약**: 마추픽추 배경 퀄리티가 우수하여, 결과 이미지 비율이 완전한 가로형(16:9)이 아니었음에도 배경을 우선하여 추가 수정 없이 확정.
- **결과 파일명**: `scene1c_keyvisual.png` / `scene1c_motion.mp4`

### Scene 1-D · 알프스 (1.5초)
- **목표 메시지**: 여정의 확장 — 네 번째 여행지이자 다음 클라이맥스 씬(설산)으로의 자연스러운 연결
- **화면 구성**: 스위스 알프스 설산 봉우리, 초원과 야생화, 인물은 화면 오른쪽 15~20% 비중으로 배치.
- **사용 도구**: GPT Image → Sora 2
- **입력 프롬프트**:
  ```
  A cinematic wide shot of the Swiss Alps landscape, snow-capped mountain peaks, green meadows with wildflowers, dramatic blue sky with soft clouds in background.
  A senior person's lower legs and feet ONLY (below the knee) positioned on the RIGHT SIDE of the frame, taking up only about 15-20% of the total frame width. The person is SMALL relative to the background. Sturdy hiking boots and wool socks visible, slightly dusty and worn.
  The LEFT SIDE and CENTER of the frame shows the full Alpine landscape clearly.
  Camera angle is low, near ground level. Rule of thirds composition — subject on right third.
  Vivid saturated colors, bright natural lighting. Landscape 16:9 ratio, 1920x1080. Photorealistic.
  ```
- **출력 결과 요약**: 별도 수정 없이 1회 생성 결과로 확정.
- **결과 파일명**: `scene1d_keyvisual.png` / `scene1d_motion.mp4`

### Scene 2 · 설산, 시니어 4인 (2초)
- **목표 메시지**: 여정의 클라이맥스 — 목적지(설산)에 도달한 시니어 그룹의 활력과 성취감을 표현하고, 다음 씬(발자국→개화)의 소재를 확보
- **화면 구성**: 눈으로 뒤덮인 알프스 설산 초입, 시니어 4인(2쌍, 컬러풀한 등산복)이 어깨동무한 채 정상을 올려다보는 전신 풀샷. 발끝까지 노출되어 눈 위 발자국이 선명하게 보임.
- **사용 도구**: GPT Image → Sora 2
- **입력 프롬프트**:
  ```
  A cinematic wide shot of four senior travelers standing on a SNOW-COVERED Alpine trail, surrounded by vast white snowy landscape.
  The entire ground is covered in deep white snow, snow-capped mountain peaks fill the background, snowy slopes and white terrain dominate the scene. Light snowfall or snow mist in the air.
  Two men and two women, all aged 60-70s, dressed in colorful winter hiking gear — red, blue, yellow, orange jackets with backpacks.
  FULL BODY SHOT — entire body visible from head to toe, boots and feet clearly visible in the snow. FOOTPRINTS clearly visible in the snow around their feet.
  They stand side by side facing AWAY from camera, arms around each other's shoulders, exactly FOUR people.
  The group occupies the BOTTOM HALF of the frame. Upper half shows dramatic snow-covered Alpine peaks, golden hour warm sky, clouds around the summits.
  Camera positioned LOW and BEHIND the group, capturing full body + snowy footprints on the ground.
  Golden hour warm lighting on snow. Vivid saturated colors, cinematic atmosphere.
  Landscape 16:9 ratio, 1920x1080. Photorealistic.
  ```
- **출력 결과 요약**: 인원 4명, 전신 풀샷, 설경과 발자국이 명확하게 표현되어 확정. 다음 씬(발자국→꽃)의 시각 소재로 연결.
- **결과 파일명**: `scene2_keyvisual.png` / `scene2_motion.mp4`

**🔁 프롬프트 수정 전/후**
- **수정 전**: 5명의 인물이 설산 "정상"에서 뒷모습으로 팔을 들거나 어깨동무. 인물이 화면 중앙에 크게 배치. — 기획 인원(4명)과 불일치, 정상 구도가 다소 무리해 보이며 지면에 눈이 충분히 덮이지 않아 이후 씬(발자국)과 연결이 약함.
- **수정 후**: 인원을 정확히 4명으로 고정, 정상이 아닌 설산 "초입"에서 위쪽을 올려다보는 구도로 변경, 지면 전체를 눈으로 덮고 전신 풀샷으로 발자국까지 노출. — 인원 정합성 확보, 자연스러운 도전/여정의 뉘앙스로 전환, 발자국이라는 다음 씬 연결 소재를 명확히 확보.

### Scene 3 · 발자국 → 꽃 개화 (1.5초)
- **목표 메시지**: 브랜드 상징 전환 — 여정(발자국)이 새로운 시작(개화)으로 바뀌는 순간을 통해 "다시 피어난다"는 브랜드 메시지를 시각화
- **화면 구성**: 눈 위에 남은 발자국이 순차적으로 꽃으로 개화하는 클로즈업. 로우앵글로 발자국 행렬이 원근감 있게 이어짐. 꽃 색상은 흰색(스노드롭)·보라색(크로커스)·노란색(윈터 재스민) 3색으로 제한, 잎사귀는 최소 노출.
- **사용 도구**: GPT Image → Sora 2
- **입력 프롬프트**:
  ```
  A magical cinematic close-up shot of footprints in white snow, each footprint filled with blooming alpine winter flowers.
  Flower species and colors STRICTLY LIMITED to three: Snowdrops (pure white), Crocus (soft purple/lavender), Winter Jasmine (pale yellow).
  MINIMAL green leaves — almost no foliage, flowers tightly packed inside each footprint shape.
  Footprints are HUMAN BOOT SHAPED — clear oval/elongated form, pressed into the snow, flowers blooming FROM INSIDE the imprint. Multiple footprints in a walking trail pattern, each at a slightly different bloom stage.
  Snow surrounds each footprint — bright white, sparkling crystalline texture. Strong contrast between pure white snow and soft flower colors.
  Camera angle: EXTREMELY LOW, almost ground level, looking along the trail of footprints stretching into the distance. Foreground footprint flowers in sharp focus, background footprints gradually blurring into soft bokeh. Shallow depth of field.
  Soft warm golden hour side lighting, magical and cinematic atmosphere.
  Vivid but restrained palette — only white, purple, yellow. Landscape 16:9 ratio, 1920x1080. Photorealistic.
  ```
- **출력 결과 요약**: 로우앵글+원근감 구도(1차)와 색상 3종 제한 규칙(2차)을 결합하여 절제되면서도 인상적인 개화 장면으로 확정.
- **결과 파일명**: `scene3_keyvisual.png` / `scene3_motion.mp4`

**🔁 프롬프트 수정 전/후**
- **수정 전**: 핑크·노랑·오렌지 등 다채로운 색상의 꽃이 자유롭게 개화, 잎사귀 다수 노출. — 색상이 지나치게 화려/다양해 브랜드 톤과 불일치, 겨울철 실제 개화 여부도 불명확.
- **수정 후**: 실제 겨울~초봄에 개화하는 꽃(스노드롭·크로커스·윈터 재스민) 중 흰색·보라·노랑 3색으로 한정, 잎사귀를 최소화. 이후 최초 구도(로우앵글·원근감)를 다시 결합. — 색상 절제로 브랜드 톤 일치, 실존 겨울꽃 기반 개연성 확보, 시네마틱한 느낌도 유지.

### Scene 4 · 로고 + 카피 + 나레이션 (2초)
- **목표 메시지**: 브랜드 각인 및 CTA — 여정의 결말을 브랜드명과 핵심 메시지로 마무리
- **화면 구성**: 흰색 배경 위, 보라·핑크 톤의 실사 질감 꽃부케(장미·피오니 혼합) 안에 "Bloom / Trip" 두 줄 로고를 두꺼운 필기체로 배치. 화면 하단 약 35% 여백에 두 줄의 한글 카피를 얹음.
- **내레이션/카피**: "당신의 두 번째 전성기 / BloomTrip과 함께, 다시 피어나세요" — 카피 자막과 나레이션 문구를 동일하게 사용하고, 나레이션 낭독 타이밍에 맞춰 자막이 순차 등장
- **사용 도구**: GPT Image(부케·로고 합성, 한글 카피는 생성형 AI의 한글 폰트 지원 한계로 사용자가 직접 오버레이) / **ElevenLabs**(나레이션 음성 합성, 변경됨) / **Suno**(영상 전체 배경음악 생성)
- **입력 프롬프트**:
  ```
  A luxury floral logo design for "BloomTrip" brand.
  Background: pure white (#FFFFFF), clean and minimal.
  Center: a lush, dense circular bouquet of purple and pink flowers (roses, peonies, anemones) in vivid violet, magenta, and lavender tones. Realistic texture, rich variety of purple tones, petals layered densely, catching soft golden light.
  Logo text: "Bloom" / "Trip" in two lines, bold thick cursive/script font, bright white color with subtle outline, placed over the center of the bouquet.
  Bottom ~35% of the image: completely empty white space reserved for Korean caption text to be added later.
  Overall composition: bouquet centered in upper ~65% of frame.
  Style: realistic, high-end, vibrant, commercial advertisement quality.
  ```
- **출력 결과 요약**: 실사 톤의 고급스러운 부케와 로고 확보, 하단 여백에 한글 카피를 얹은 뒤 필기체 폰트를 더 두껍게 재조정하여 최종 확정.
- **결과 파일명**: `scene4_logo.png` / `narration_scene4.mp3`

## 6. 최종 영상 파일 정보

| 항목 | 내용 |
|---|---|
| 파일명 | 최종본.mp4 |
| 길이 | 약 11.98초 |
| 해상도 | 1920 × 1080 (1080p) |
| 프레임레이트 | 약 29.97fps |
| 비디오 코덱 | H.264 |
| 오디오 코덱 | AAC |

## 7. 제작 전략 및 유의사항

- 이미지 생성(GPT Image) 단계에서 각 씬의 구도·색상·인물 노출 범위를 충분히 확정한 뒤, Sora 2로 영상 변환을 진행하여 영상 생성 크레딧 소모를 최소화함.
- Scene 1의 A~D(유럽·지중해·남미·알프스) 전 씬에 걸쳐 "인물은 화면 오른쪽에 작게, 배경이 주인공"이라는 동일한 구도 규칙을 재사용하여 캐릭터·스타일 일관성을 확보함.
- 생성형 AI의 한글 텍스트 렌더링 한계로, Scene 4의 한글 카피는 AI 생성 이미지 위에 사용자가 직접 오버레이하는 방식으로 대응함.
- 기존에 사용하려던 OpenAI 계열 네이티브 오디오 생성 프로그램(GPT-4o mini TTS)의 토큰(크레딧)이 부족해져, 나레이션은 ElevenLabs로, 배경음악은 Suno로 대체 도구를 활용함(도구 접근성 제약에 대한 대응 사례).
- 모든 시각·청각 소스는 GPT Image·Sora 2·Suno·ElevenLabs의 생성 결과물을 주 소스로 사용하였으며, 직접 촬영본이나 유료 스톡 소스는 사용하지 않음.
- 영상 편집 소프트웨어(CapCut)는 컷 연결, 한글 자막 합성, BGM/오디오 레벨 조정 등 통합 편집 용도로만 제한적으로 사용함.

---
*문서 작성일: 2026년 7월 19일*
