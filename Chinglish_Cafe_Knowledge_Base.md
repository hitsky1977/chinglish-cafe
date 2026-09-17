# Chinglish.Cafe Project Context & Knowledge Base

&gt; Last Updated: 2026-09-17
&gt; Status: SYNCED with content/posts/ (153 published entries)

## 1. Project Overview
*   **Site Name:** Chinglish.Cafe
*   **Tagline:** The Ultimate Dictionary of Chinese-English Slang & Translation Fails
*   **Target Audience:** International English speakers (foreigners), linguists, and culture enthusiasts.
*   **Tone of Voice:** Humorous, cultural, slightly academic but highly engaging.
*   **Core Goal:** To archive literal translations, internet slang, borrowed words, and historical pidgin phrases that showcase the humor and creativity of the Chinese language meeting the English world.
*   **Brand Narrative:** Chinglish is not "bad English." The site is a cultural archive of **English expressions born from Chinese logic**, built on two parallel storylines:
    *   **Chinglish** — English reshaped by Chinese logic (literal translations, internet slang, pidgin heritage). Comedy of collision.
    *   **English from China** — words China gave to standard English (loanwords). China's real footprint on global English.

## 2. Two Entry Types & Their Front Matter Schemas
The dictionary has **two series with different schemas and body structures**. Identify the correct type BEFORE writing.

### 2.1 Chinglish series (category: Idioms & Slang / Internet Slang / Daily Life)
```yaml
---
title: "English Literal Translation Here"
date: YYYY-MM-DDTHH:MM:SS+08:00
category: ["Idioms & Slang"]        # or ["Internet Slang"] / ["Daily Life"]
series: ["Chinglish"]
tags: ["Chinglish", "tag1", "tag2"]
chinglish_phrase: "The exact Chinglish phrase"
chinese_meaning: "中文词义 (pinyin)"
native_expression: "The natural/native English equivalent"
is_dictionary_added: false           # true ONLY if added to Oxford/OED etc.
humor_index: 3                       # integer 1-5; use 5 only for truly top-tier comedy
example_sentence: "A practical English example sentence."
---
```
Body sections (in this order):
1. `## 📖 Origin Story` — historical/cultural background of the Chinese source.
2. `## 🤓 Analysis & Usage` — grammar (or lack thereof), why the literal translation is funny/interesting.
3. `## ✍️ Usage in Context` — modern usage + an **Example Conversation** (humorous dialogue script, 4-8 lines).

### 2.2 English from China series (category: Culture)
```yaml
---
title: "Loanword"
date: YYYY-MM-DDTHH:MM:SS+08:00
category: ["Culture"]
series: ["English from China"]
english_phrase: "Loanword"
chinese_origin: "中文源词 (pinyin) — dialect note if Cantonese/Hokkien etc."
notability: 3                        # integer 1-5
native_expression: "Standard English equivalent / category"
example_sentence: "A practical English example sentence."
source: "Etymology source / route into English"
year: "Century or year of entry into English"
description: "One-sentence SEO/social description."
---
```
Body sections (in this order):
1. `## 📖 Origin Story` — the etymology detective story.
2. `## 🌍 Why It Matters` — cultural significance, hidden Chinese influence.
3. `## ✍️ Usage in Context` — usage examples, often as short dialogue scenes.

## 3. Conventions
*   **File naming:** lowercase, hyphenated slug = English literal translation (`cover-ear-steal-bell.md`). Slug must be unique site-wide.
*   **URLs:** permalinks strip `/posts/` — entry URL is `/slug/`. Internal links always use root-absolute paths: `[Add Oil](/add-oil/)`.
*   **Categories:** exactly 4 values exist — `Culture`, `Idioms & Slang`, `Internet Slang`, `Daily Life`. (Legacy values "Workplace" and "Other" are retired; do not use.)
*   **Series:** exactly 2 values — `Chinglish`, `English from China`.
*   **Language:** entry body is pure English. Operational/config comments may be Chinese.
*   **Articles** (long-form) live in `content/articles/`, category `["Feature"]`, listed at `/extra-credit/`.

## 4. Existing Entries Index (Do NOT Duplicate — 153 total)

### 4.1 Series: Chinglish (88 entries)

#### Category: Idioms & Slang (47)
- 0.5 Yes 0.5 No (半信半疑) — /0-5-yes-0-5-no/
- All Money Back My Home (恭喜发财/财归我家) — /all-money-back-my-home/
- Blow Cow (吹牛) — /blow-cow/
- Cover Ear Steal Bell (掩耳盗铃) — /cover-ear-steal-bell/
- Cup Bow Snake Shadow (杯弓蛇影) — /cup-bow-snake-shadow/
- You Dida-dida Me, I Huala-huala You (滴水之恩，当涌泉相报) — /dida-huala/
- Dragon Born Dragon (龙生龙，凤生凤…) — /dragon-born-dragon/
- Draw Snake Add Feet (画蛇添足) — /draw-snake-add-feet/
- Eat Vinegar (吃醋) — /eat-vinegar/
- Fox Borrows Tiger's Might (狐假虎威) — /fox-borrows-tiger-might/
- Frog at the Bottom of a Well (井底之蛙) — /frog-at-the-bottom-of-a-well/
- Gaze at Plums to Quench Thirst (望梅止渴) — /gaze-at-plums-to-quench-thirst/
- Go and Look (走着瞧) — /go-and-look/
- Guard Tree Stump Wait Rabbit (守株待兔) — /guard-tree-stump-wait-rabbit/
- Heart Flower Angry Open (心花怒放) — /heart-flower-angry-open/
- Lord Ye Loves Dragons (叶公好龙) — /lord-ye-loves-dragons/
- Love Who Who (爱谁谁) — /love-who-who/
- Mark Boat to Find Sword (刻舟求剑) — /mark-boat-find-sword/
- Morning Three Night Four (朝三暮四) — /morning-three-night-four/
- No JJ Book (葵花宝典/辟邪剑谱) — /no-jj-book/
- No Money No Talk (没钱免谈) — /no-money-no-talk/
- No Three No Four (不三不四) — /no-three-no-four/
- Nonsense Eight Ways (胡说八道) — /nonsense-eight-ways/
- Old Ginger Is Spicy (姜还是老的辣) — /old-ginger-is-spicy/
- One Don't Do, Two Don't Stop (一不做二不休) — /one-dont-do-two-dont-stop/
- One Head Fog Water (一头雾水) — /one-head-fog-water/
- One Word Go, Jia Jia Jia (一言既出，驷马难追) — /one-word-go-jia/
- Open Door See Mountain (开门见山) — /open-door-see-mountain/
- Papa No Baby (不孕不育) — /papa-no-baby/
- Paper Tiger (纸老虎) — /paper-tiger/
- Play Piano to a Cow (对牛弹琴) — /play-piano-to-a-cow/
- Point Deer Call Horse (指鹿为马) — /point-deer-call-horse/
- Pour Cold Water (泼冷水) — /pour-cold-water/
- Qi People Worry About Sky (杞人忧天) — /qi-people-worry-sky/
- Self-Contradicting Spear and Shield (自相矛盾) — /self-contradicting-spear-shield/
- Send Charcoal in Snow (雪中送炭) — /send-charcoal-in-snow/
- Seven Up Eight Down (七上八下) — /seven-up-eight-down/
- Show Axe at Ban's Door (班门弄斧) — /show-axe-at-bans-door/
- Smell Smelly, Taste Tasty (闻着臭，吃着香) — /smell-smelly-taste-tasty/
- We Two Who And Who (我俩谁跟谁) — /we-two-who-and-who/
- Wear Small Shoes (穿小鞋) — /wear-small-shoes/
- Where Cool Where You Stay (哪儿凉快哪儿待着去) — /where-cool-where-stay/
- Wind Horse Cow Not Related (风马牛不相及) — /wind-horse-cow-not-related/
- You Can Kill Me, But You Can Not Fuck Me — /you-can-kill-me/
- You Don't Bird Me, I Don't Bird You (你不鸟我，我也不鸟你) — /you-dont-bird-me/
- You Me You Me (彼此彼此) — /you-me-you-me/
- You Swan, He Frog (癞蛤蟆想吃天鹅肉) — /you-swan-he-frog/

#### Category: Internet Slang (25)
- Chinglish (中式英语) — /chinglish/
- Dog Food (狗粮) — /dog-food/
- Family 4.0 (四世同堂) — /family-4-0/
- Fast Fast as Biu Biu (急急如律令) — /fast-fast-as-biu-biu/
- Geilivable (给力/不给力) — /geilivable/
- Glass Heart (玻璃心) — /glass-heart/
- Go past no mistake past (走过路过，不要错过) — /go-past-no-mistake-past/
- God is a girl (上帝不公) — /god-is-a-girl/
- Green Tea Bitch (绿茶婊) — /green-tea-bitch/
- How are you? How old are you? (怎么是你？怎么老是你？) — /how-are-you/
- Know is know, no know is no know (知之为知之…) — /know-is-know/
- Laugh to Pee (笑尿了) — /laugh-to-pee/
- Lying Flat (躺平) — /lying-flat/
- Middle Two (中二) — /middle-two/
- Niubility (牛逼) — /niubility/
- No Zuo No Die (不作死就不会死) — /no-zuo-no-die/
- Old Driver (老司机) — /old-driver/
- One day teacher, day day father (一日为师，终身为父) — /one-day-teacher/
- Salted Fish (咸鱼) — /salted-fish/
- Smilence (笑而不语) — /smilence/
- Social Death (社死) — /social-death/
- Tree new bee (吹牛皮) — /tree-new-bee/
- Versailles (凡尔赛) — /versailles/
- You Can You Up, No Can No BB (你行你上) — /you-can-you-up/
- YYDS (永远的神) — /yyds/

#### Category: Daily Life (16)
- Add Oil (加油) — /add-oil/
- Fight Chicken Blood (打鸡血) — /fight-chicken-blood/
- Fuck the Duck Until Exploded (干炸鸭子) — /fuck-the-duck-until-exploded/
- Good Good Study, Day Day Up (好好学习，天天向上) — /good-study-day-up/
- Horse Horse Tiger Tiger (马马虎虎) — /horse-horse-tiger-tiger/
- Leftover Woman (剩女) — /leftover-woman/
- Let the Horse Come Here (放马过来) — /let-horse-come-here/
- Long Time No See (好久不见) — /long-time-no-see/
- Lose Face (丢脸) — /lose-face/
- No Can Do (不行) — /no-can-do/
- Open Water (开水) — /open-water/
- People Mountain People Sea (人山人海) — /people-mountain-people-sea/
- Give You Some Color to See See (给你点颜色看看) — /some-color-to-see/
- Touch Porcelain (碰瓷) — /touch-porcelain/
- VIP Dog (贵宾犬) — /vip-dog/
- Watch Sister (表妹) — /watch-sister/

### 4.2 Series: English from China (65 entries, all Category: Culture)
- Baijiu (白酒) — /baijiu/
- Baozi / Bao (包子) — /bao/
- Barefoot Doctor (赤脚医生) — /barefoot-doctor/
- Be water, my friend (像水一样) — /be-water-my-friend/
- Boba / Bubble Tea (波霸奶茶) — /boba/
- Bok Choy (白菜, Cantonese) — /bok-choy/
- Char Siu (叉烧, Cantonese) — /char-siu/
- Cheongsam (长衫, Cantonese) — /cheongsam/
- China (昌南/瓷器) — /china/
- Chinatown (唐人街) — /chinatown/
- Chop-Chop (速速/快快, Cantonese) — /chop-chop/
- Chop Suey (杂碎) — /chop-suey/
- Chow mein (炒面, Cantonese) — /chow-mein/
- Confucius (孔夫子) — /confucius/
- Congee (粥) — /congee/
- Dama (大妈) — /dama/
- Danwei (单位) — /danwei/
- Dim sum (点心, Cantonese) — /dim-sum/
- Durian (榴莲) — /durian/
- Erhu (二胡) — /erhu/
- Feng shui (风水) — /feng-shui/
- Goji (枸杞) — /goji/
- Guanxi (关系) — /guanxi/
- Hongbao (红包) — /hongbao/
- Hot Pot (火锅) — /hot-pot/
- Hukou (户口) — /hukou/
- Hutong (胡同) — /hutong/
- Involution (内卷) — /involution/
- Iron Rice Bowl (铁饭碗) — /iron-rice-bowl/
- Jiaozi (饺子) — /jiaozi/
- Jin (斤) — /jin/
- Ketchup (鮭汁/茄汁, Hokkien) — /ketchup/
- Koi Fish (锦鲤) — /koi-fish/
- Kowtow (叩头) — /kowtow/
- Kumquat (金橘, Cantonese) — /kumquat/
- Kung fu (功夫) — /kung-fu/
- Li (里) — /li/
- Loong (龙) — /loong/
- Lychee (荔枝) — /lychee/
- Mahjong (麻将) — /mahjong/
- Mandarin (满大人/官话) — /mandarin/
- Mooncake (月饼) — /mooncake/
- Oolong (乌龙) — /oolong/
- Ping Pong (乒乓) — /ping-pong/
- Pipa (琵琶) — /pipa/
- Qi / Chi (气) — /qi/
- Qipao (旗袍) — /qipao/
- Rambutan (红毛丹) — /rambutan/
- Running dog (走狗) — /running-dog/
- Shanghaied (上海) — /shanghaied/
- Shanshui (山水) — /shanshui/
- Sifu (师傅/師父) — /sifu/
- Silk Road (丝绸之路) — /silk-road/
- Tai chi (太极) — /tai-chi/
- Tao / Dao (道) — /tao/
- Tea (茶) — /tea/
- Tofu (豆腐) — /tofu/
- Tongzhi (同志) — /tongzhi/
- Tuhao (土豪) — /tuhao/
- Typhoon (大风/台风) — /typhoon/
- Wonton (馄饨, Cantonese) — /wonton/
- Wuxia (武侠) — /wuxia/
- Yin-yang (阴阳) — /yin-yang/
- Yuan (元) — /yuan/
- Zen (禅) — /zen/

## 5. Writing Backlog (candidates, no entry yet)
Idioms listed on /chinese-idioms-in-english/ without a dedicated entry yet:
- 拍马屁 — Pat Horse Butt (flattery)
- 碰钉子 — Hit Nail (be rejected)
- 打草惊蛇 — Beat Grass Startle Snake (alert the enemy)
- 杀鸡取卵 — Kill Chicken Take Egg (kill the golden goose)
- 亡羊补牢 — Mend Pen After Sheep Lost (better late than never)
General directions: fresh Chinese internet slang (fastest-moving category), deeper Culture loanword lines (festivals, zodiac, dialect words), and /extra-credit/ long-form follow-ups.

## 6. Change Log
- 2026-09-17: Full rebuild. Synced index to all 153 posts; replaced legacy categories (Workplace/Other) with the live 4-category system; split schema into the two live templates (Chinglish / English from China); retired single-string `category` format in favor of list format.