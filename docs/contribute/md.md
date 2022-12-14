---
title: 文档使用指南
---

<Contributors :names="['虚位以待']" />

# 文档使用指南

如果有语法方面的使用问题，你可以直接在群里@我。

这里比较有用的是 [自定义容器](#扩展-自定义容器1)

## Markdown语法

首先是[Markdown 基础语法](https://gitee.com/wellfrog16/thu-xyj/blob/master/MDHelp.md)

## 扩展：自定义容器1

### 游戏的信息展示

如果你想要复制游戏里的信息到文档里，你可以使用下面这个容器包裹，后续还会对该容器增加字符颜色等功能

使用 **&#096;&#096;&#096;mud** 和 **&#096;&#096;&#096;** 包裹起来

```md
```mud
 气血：  250/  250 (100%)    内力：  500 /    0 (100%) (+0)
 精神：  200/  200 (100%)    法力：  500 /    0 (100%) (+0)
 食物：  227/  350           武学： 400300
 饮水：    0/  350           道行： 四百年七十五天
 潜能： 400579               杀气： 0
`` `(去掉空格)
```

上面的信息，实际被预览时会渲染成

```mud
 气血：  250/  250 (100%)    内力：  500 /    0 (100%) (+0)
 精神：  200/  200 (100%)    法力：  500 /    0 (100%) (+0)
 食物：  227/  350           武学： 400300
 饮水：    0/  350           道行： 四百年七十五天
 潜能： 400579               杀气： 0
```

### 文本信息单独排版

如果你想要使用多行文本进行排版，并非游戏中的信息，避免 md 文档的段落换行。

你可以使用 **&#096;&#096;&#096;content** 和 **&#096;&#096;&#096;** 包裹起来

```md
```content
灵台方寸山，
斜月三星洞。
盘丝洞七情迷本，
濯垢泉八戒忘形。
`` `(去掉空格)
```

上面的信息，实际被预览时会渲染成

```content
灵台方寸山，
斜月三星洞。
盘丝洞七情迷本，
濯垢泉八戒忘形。
```

## 扩展：自定义容器2

```md
::: tip
这是一条提示信息
:::

::: warning
这是一条警告信息
:::

::: danger
这是一条严重警告信息
:::

:::reference
落霞与孤鹜齐飞，秋水共长天一色。

出自王勃《滕王阁序》
:::

::: details
这是一个 details 标签
:::
```

渲染结果如下所示：

::: tip
这是一条提示信息
:::

::: warning
这是一条警告信息
:::

::: danger
这是一条严重警告信息
:::

:::reference
落霞与孤鹜齐飞，秋水共长天一色。

出自王勃《滕王阁序》
:::

::: details
这是一个 details 标签
:::

## Emoji :parasol_on_ground:

你可以使用 Emoji 表情来装饰你的内容，有少量无法正常显示可以忽略:rofl:

:::warning
emoji 表情无法用于特殊的内容里
:::

### 脸部表情 :blush:

#### Face Smiling

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :grinning: | `:grinning:` | :smiley: | `:smiley:` |
| :smile: | `:smile:` | :grin: | `:grin:` |
| :laughing: | `:laughing:` <br /> `:satisfied:` | :sweat_smile: | `:sweat_smile:` |
| :rofl: | `:rofl:` | :joy: | `:joy:` |
| :slightly_smiling_face: | `:slightly_smiling_face:` | :upside_down_face: | `:upside_down_face:` |
| :wink: | `:wink:` | :blush: | `:blush:` |
| :innocent: | `:innocent:` | | |

#### Face Affection

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :smiling_face_with_three_hearts: | `:smiling_face_with_three_hearts:` | :heart_eyes: | `:heart_eyes:` |
| :star_struck: | `:star_struck:` | :kissing_heart: | `:kissing_heart:` |
| :kissing: | `:kissing:` | :relaxed: | `:relaxed:` |
| :kissing_closed_eyes: | `:kissing_closed_eyes:` | :kissing_smiling_eyes: | `:kissing_smiling_eyes:` |
| :smiling_face_with_tear: | `:smiling_face_with_tear:` | | |

#### Face Tongue

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :yum: | `:yum:` | :stuck_out_tongue: | `:stuck_out_tongue:` |
| :stuck_out_tongue_winking_eye: | `:stuck_out_tongue_winking_eye:` | :zany_face: | `:zany_face:` |
| :stuck_out_tongue_closed_eyes: | `:stuck_out_tongue_closed_eyes:` | :money_mouth_face: | `:money_mouth_face:` |

#### Face Hand

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :hugs: | `:hugs:` | :hand_over_mouth: | `:hand_over_mouth:` |
| :shushing_face: | `:shushing_face:` | :thinking: | `:thinking:` |

#### Face Neutral Skeptical

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :zipper_mouth_face: | `:zipper_mouth_face:` | :raised_eyebrow: | `:raised_eyebrow:` |
| :neutral_face: | `:neutral_face:` | :expressionless: | `:expressionless:` |
| :no_mouth: | `:no_mouth:` | :face_in_clouds: | `:face_in_clouds:` |
| :smirk: | `:smirk:` | :unamused: | `:unamused:` |
| :roll_eyes: | `:roll_eyes:` | :grimacing: | `:grimacing:` |
| :face_exhaling: | `:face_exhaling:` | :lying_face: | `:lying_face:` |

#### Face Sleepy

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :relieved: | `:relieved:` | :pensive: | `:pensive:` |
| :sleepy: | `:sleepy:` | :drooling_face: | `:drooling_face:` |
| :sleeping: | `:sleeping:` | | |

#### Face Unwell

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :mask: | `:mask:` | :face_with_thermometer: | `:face_with_thermometer:` |
| :face_with_head_bandage: | `:face_with_head_bandage:` | :nauseated_face: | `:nauseated_face:` |
| :vomiting_face: | `:vomiting_face:` | :sneezing_face: | `:sneezing_face:` |
| :hot_face: | `:hot_face:` | :cold_face: | `:cold_face:` |
| :woozy_face: | `:woozy_face:` | :dizzy_face: | `:dizzy_face:` |
| :face_with_spiral_eyes: | `:face_with_spiral_eyes:` | :exploding_head: | `:exploding_head:` |

#### Face Hat

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :cowboy_hat_face: | `:cowboy_hat_face:` | :partying_face: | `:partying_face:` |
| :disguised_face: | `:disguised_face:` | | |

#### Face Glasses

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :sunglasses: | `:sunglasses:` | :nerd_face: | `:nerd_face:` |
| :monocle_face: | `:monocle_face:` | | |

#### Face Concerned

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :confused: | `:confused:` | :worried: | `:worried:` |
| :slightly_frowning_face: | `:slightly_frowning_face:` | :frowning_face: | `:frowning_face:` |
| :open_mouth: | `:open_mouth:` | :hushed: | `:hushed:` |
| :astonished: | `:astonished:` | :flushed: | `:flushed:` |
| :pleading_face: | `:pleading_face:` | :frowning: | `:frowning:` |
| :anguished: | `:anguished:` | :fearful: | `:fearful:` |
| :cold_sweat: | `:cold_sweat:` | :disappointed_relieved: | `:disappointed_relieved:` |
| :cry: | `:cry:` | :sob: | `:sob:` |
| :scream: | `:scream:` | :confounded: | `:confounded:` |
| :persevere: | `:persevere:` | :disappointed: | `:disappointed:` |
| :sweat: | `:sweat:` | :weary: | `:weary:` |
| :tired_face: | `:tired_face:` | :yawning_face: | `:yawning_face:` |

#### Face Negative

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :triumph: | `:triumph:` | :pout: | `:pout:` <br /> `:rage:` |
| :angry: | `:angry:` | :cursing_face: | `:cursing_face:` |
| :smiling_imp: | `:smiling_imp:` | :imp: | `:imp:` |
| :skull: | `:skull:` | :skull_and_crossbones: | `:skull_and_crossbones:` |

#### Face Costume

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :hankey: | `:hankey:` <br /> `:poop:` <br /> `:shit:` | :clown_face: | `:clown_face:` |
| :japanese_ogre: | `:japanese_ogre:` | :japanese_goblin: | `:japanese_goblin:` |
| :ghost: | `:ghost:` | :alien: | `:alien:` |
| :space_invader: | `:space_invader:` | :robot: | `:robot:` |

#### Cat Face

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :smiley_cat: | `:smiley_cat:` | :smile_cat: | `:smile_cat:` |
| :joy_cat: | `:joy_cat:` | :heart_eyes_cat: | `:heart_eyes_cat:` |
| :smirk_cat: | `:smirk_cat:` | :kissing_cat: | `:kissing_cat:` |
| :scream_cat: | `:scream_cat:` | :crying_cat_face: | `:crying_cat_face:` |
| :pouting_cat: | `:pouting_cat:` | | |

#### Monkey Face

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :see_no_evil: | `:see_no_evil:` | :hear_no_evil: | `:hear_no_evil:` |
| :speak_no_evil: | `:speak_no_evil:` | | |

#### Emotion

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :kiss: | `:kiss:` | :love_letter: | `:love_letter:` |
| :cupid: | `:cupid:` | :gift_heart: | `:gift_heart:` |
| :sparkling_heart: | `:sparkling_heart:` | :heartpulse: | `:heartpulse:` |
| :heartbeat: | `:heartbeat:` | :revolving_hearts: | `:revolving_hearts:` |
| :two_hearts: | `:two_hearts:` | :heart_decoration: | `:heart_decoration:` |
| :heavy_heart_exclamation: | `:heavy_heart_exclamation:` | :broken_heart: | `:broken_heart:` |
| :heart_on_fire: | `:heart_on_fire:` | :mending_heart: | `:mending_heart:` |
| :heart: | `:heart:` | :orange_heart: | `:orange_heart:` |
| :yellow_heart: | `:yellow_heart:` | :green_heart: | `:green_heart:` |
| :blue_heart: | `:blue_heart:` | :purple_heart: | `:purple_heart:` |
| :brown_heart: | `:brown_heart:` | :black_heart: | `:black_heart:` |
| :white_heart: | `:white_heart:` | :100: | `:100:` |
| :anger: | `:anger:` | :boom: | `:boom:` <br /> `:collision:` |
| :dizzy: | `:dizzy:` | :sweat_drops: | `:sweat_drops:` |
| :dash: | `:dash:` | :hole: | `:hole:` |
| :bomb: | `:bomb:` | :speech_balloon: | `:speech_balloon:` |
| :eye_speech_bubble: | `:eye_speech_bubble:` | :left_speech_bubble: | `:left_speech_bubble:` |
| :right_anger_bubble: | `:right_anger_bubble:` | :thought_balloon: | `:thought_balloon:` |
| :zzz: | `:zzz:` | | |

### 人物和身体 :ok_woman:

#### Hand Fingers Open

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :wave: | `:wave:` | :raised_back_of_hand: | `:raised_back_of_hand:` |
| :raised_hand_with_fingers_splayed: | `:raised_hand_with_fingers_splayed:` | :hand: | `:hand:` <br /> `:raised_hand:` |
| :vulcan_salute: | `:vulcan_salute:` | | |

#### Hand Fingers Partial

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :ok_hand: | `:ok_hand:` | :pinched_fingers: | `:pinched_fingers:` |
| :pinching_hand: | `:pinching_hand:` | :v: | `:v:` |
| :crossed_fingers: | `:crossed_fingers:` | :love_you_gesture: | `:love_you_gesture:` |
| :metal: | `:metal:` | :call_me_hand: | `:call_me_hand:` |

#### Hand Single Finger

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :point_left: | `:point_left:` | :point_right: | `:point_right:` |
| :point_up_2: | `:point_up_2:` | :fu: | `:fu:` <br /> `:middle_finger:` |
| :point_down: | `:point_down:` | :point_up: | `:point_up:` |

#### Hand Fingers Closed

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :+1: | `:+1:` <br /> `:thumbsup:` | :-1: | `:-1:` <br /> `:thumbsdown:` |
| :fist: | `:fist:` <br /> `:fist_raised:` | :facepunch: | `:facepunch:` <br /> `:fist_oncoming:` <br /> `:punch:` |
| :fist_left: | `:fist_left:` | :fist_right: | `:fist_right:` |

#### Hands

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :clap: | `:clap:` | :raised_hands: | `:raised_hands:` |
| :open_hands: | `:open_hands:` | :palms_up_together: | `:palms_up_together:` |
| :handshake: | `:handshake:` | :pray: | `:pray:` |

#### Hand Prop

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :writing_hand: | `:writing_hand:` | :nail_care: | `:nail_care:` |
| :selfie: | `:selfie:` | | |

#### Body Parts

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :muscle: | `:muscle:` | :mechanical_arm: | `:mechanical_arm:` |
| :mechanical_leg: | `:mechanical_leg:` | :leg: | `:leg:` |
| :foot: | `:foot:` | :ear: | `:ear:` |
| :ear_with_hearing_aid: | `:ear_with_hearing_aid:` | :nose: | `:nose:` |
| :brain: | `:brain:` | :anatomical_heart: | `:anatomical_heart:` |
| :lungs: | `:lungs:` | :tooth: | `:tooth:` |
| :bone: | `:bone:` | :eyes: | `:eyes:` |
| :eye: | `:eye:` | :tongue: | `:tongue:` |
| :lips: | `:lips:` | | |

#### Person

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :baby: | `:baby:` | :child: | `:child:` |
| :boy: | `:boy:` | :girl: | `:girl:` |
| :adult: | `:adult:` | :blond_haired_person: | `:blond_haired_person:` |
| :man: | `:man:` | :bearded_person: | `:bearded_person:` |
| :man_beard: | `:man_beard:` | :woman_beard: | `:woman_beard:` |
| :red_haired_man: | `:red_haired_man:` | :curly_haired_man: | `:curly_haired_man:` |
| :white_haired_man: | `:white_haired_man:` | :bald_man: | `:bald_man:` |
| :woman: | `:woman:` | :red_haired_woman: | `:red_haired_woman:` |
| :person_red_hair: | `:person_red_hair:` | :curly_haired_woman: | `:curly_haired_woman:` |
| :person_curly_hair: | `:person_curly_hair:` | :white_haired_woman: | `:white_haired_woman:` |
| :person_white_hair: | `:person_white_hair:` | :bald_woman: | `:bald_woman:` |
| :person_bald: | `:person_bald:` | :blond_haired_woman: | `:blond_haired_woman:` <br /> `:blonde_woman:` |
| :blond_haired_man: | `:blond_haired_man:` | :older_adult: | `:older_adult:` |
| :older_man: | `:older_man:` | :older_woman: | `:older_woman:` |

#### Person Gesture

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :frowning_person: | `:frowning_person:` | :frowning_man: | `:frowning_man:` |
| :frowning_woman: | `:frowning_woman:` | :pouting_face: | `:pouting_face:` |
| :pouting_man: | `:pouting_man:` | :pouting_woman: | `:pouting_woman:` |
| :no_good: | `:no_good:` | :ng_man: | `:ng_man:` <br /> `:no_good_man:` |
| :ng_woman: | `:ng_woman:` <br /> `:no_good_woman:` | :ok_person: | `:ok_person:` |
| :ok_man: | `:ok_man:` | :ok_woman: | `:ok_woman:` |
| :information_desk_person: | `:information_desk_person:` <br /> `:tipping_hand_person:` | :sassy_man: | `:sassy_man:` <br /> `:tipping_hand_man:` |
| :sassy_woman: | `:sassy_woman:` <br /> `:tipping_hand_woman:` | :raising_hand: | `:raising_hand:` |
| :raising_hand_man: | `:raising_hand_man:` | :raising_hand_woman: | `:raising_hand_woman:` |
| :deaf_person: | `:deaf_person:` | :deaf_man: | `:deaf_man:` |
| :deaf_woman: | `:deaf_woman:` | :bow: | `:bow:` |
| :bowing_man: | `:bowing_man:` | :bowing_woman: | `:bowing_woman:` |
| :facepalm: | `:facepalm:` | :man_facepalming: | `:man_facepalming:` |
| :woman_facepalming: | `:woman_facepalming:` | :shrug: | `:shrug:` |
| :man_shrugging: | `:man_shrugging:` | :woman_shrugging: | `:woman_shrugging:` |

#### Person Role

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :health_worker: | `:health_worker:` | :man_health_worker: | `:man_health_worker:` |
| :woman_health_worker: | `:woman_health_worker:` | :student: | `:student:` |
| :man_student: | `:man_student:` | :woman_student: | `:woman_student:` |
| :teacher: | `:teacher:` | :man_teacher: | `:man_teacher:` |
| :woman_teacher: | `:woman_teacher:` | :judge: | `:judge:` |
| :man_judge: | `:man_judge:` | :woman_judge: | `:woman_judge:` |
| :farmer: | `:farmer:` | :man_farmer: | `:man_farmer:` |
| :woman_farmer: | `:woman_farmer:` | :cook: | `:cook:` |
| :man_cook: | `:man_cook:` | :woman_cook: | `:woman_cook:` |
| :mechanic: | `:mechanic:` | :man_mechanic: | `:man_mechanic:` |
| :woman_mechanic: | `:woman_mechanic:` | :factory_worker: | `:factory_worker:` |
| :man_factory_worker: | `:man_factory_worker:` | :woman_factory_worker: | `:woman_factory_worker:` |
| :office_worker: | `:office_worker:` | :man_office_worker: | `:man_office_worker:` |
| :woman_office_worker: | `:woman_office_worker:` | :scientist: | `:scientist:` |
| :man_scientist: | `:man_scientist:` | :woman_scientist: | `:woman_scientist:` |
| :technologist: | `:technologist:` | :man_technologist: | `:man_technologist:` |
| :woman_technologist: | `:woman_technologist:` | :singer: | `:singer:` |
| :man_singer: | `:man_singer:` | :woman_singer: | `:woman_singer:` |
| :artist: | `:artist:` | :man_artist: | `:man_artist:` |
| :woman_artist: | `:woman_artist:` | :pilot: | `:pilot:` |
| :man_pilot: | `:man_pilot:` | :woman_pilot: | `:woman_pilot:` |
| :astronaut: | `:astronaut:` | :man_astronaut: | `:man_astronaut:` |
| :woman_astronaut: | `:woman_astronaut:` | :firefighter: | `:firefighter:` |
| :man_firefighter: | `:man_firefighter:` | :woman_firefighter: | `:woman_firefighter:` |
| :cop: | `:cop:` <br /> `:police_officer:` | :policeman: | `:policeman:` |
| :policewoman: | `:policewoman:` | :detective: | `:detective:` |
| :male_detective: | `:male_detective:` | :female_detective: | `:female_detective:` |
| :guard: | `:guard:` | :guardsman: | `:guardsman:` |
| :guardswoman: | `:guardswoman:` | :ninja: | `:ninja:` |
| :construction_worker: | `:construction_worker:` | :construction_worker_man: | `:construction_worker_man:` |
| :construction_worker_woman: | `:construction_worker_woman:` | :prince: | `:prince:` |
| :princess: | `:princess:` | :person_with_turban: | `:person_with_turban:` |
| :man_with_turban: | `:man_with_turban:` | :woman_with_turban: | `:woman_with_turban:` |
| :man_with_gua_pi_mao: | `:man_with_gua_pi_mao:` | :woman_with_headscarf: | `:woman_with_headscarf:` |
| :person_in_tuxedo: | `:person_in_tuxedo:` | :man_in_tuxedo: | `:man_in_tuxedo:` |
| :woman_in_tuxedo: | `:woman_in_tuxedo:` | :person_with_veil: | `:person_with_veil:` |
| :man_with_veil: | `:man_with_veil:` | :bride_with_veil: | `:bride_with_veil:` <br /> `:woman_with_veil:` |
| :pregnant_woman: | `:pregnant_woman:` | :breast_feeding: | `:breast_feeding:` |
| :woman_feeding_baby: | `:woman_feeding_baby:` | :man_feeding_baby: | `:man_feeding_baby:` |
| :person_feeding_baby: | `:person_feeding_baby:` | | |

#### Person Fantasy

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :angel: | `:angel:` | :santa: | `:santa:` |
| :mrs_claus: | `:mrs_claus:` | :mx_claus: | `:mx_claus:` |
| :superhero: | `:superhero:` | :superhero_man: | `:superhero_man:` |
| :superhero_woman: | `:superhero_woman:` | :supervillain: | `:supervillain:` |
| :supervillain_man: | `:supervillain_man:` | :supervillain_woman: | `:supervillain_woman:` |
| :mage: | `:mage:` | :mage_man: | `:mage_man:` |
| :mage_woman: | `:mage_woman:` | :fairy: | `:fairy:` |
| :fairy_man: | `:fairy_man:` | :fairy_woman: | `:fairy_woman:` |
| :vampire: | `:vampire:` | :vampire_man: | `:vampire_man:` |
| :vampire_woman: | `:vampire_woman:` | :merperson: | `:merperson:` |
| :merman: | `:merman:` | :mermaid: | `:mermaid:` |
| :elf: | `:elf:` | :elf_man: | `:elf_man:` |
| :elf_woman: | `:elf_woman:` | :genie: | `:genie:` |
| :genie_man: | `:genie_man:` | :genie_woman: | `:genie_woman:` |
| :zombie: | `:zombie:` | :zombie_man: | `:zombie_man:` |
| :zombie_woman: | `:zombie_woman:` | | |

#### Person Activity

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :massage: | `:massage:` | :massage_man: | `:massage_man:` |
| :massage_woman: | `:massage_woman:` | :haircut: | `:haircut:` |
| :haircut_man: | `:haircut_man:` | :haircut_woman: | `:haircut_woman:` |
| :walking: | `:walking:` | :walking_man: | `:walking_man:` |
| :walking_woman: | `:walking_woman:` | :standing_person: | `:standing_person:` |
| :standing_man: | `:standing_man:` | :standing_woman: | `:standing_woman:` |
| :kneeling_person: | `:kneeling_person:` | :kneeling_man: | `:kneeling_man:` |
| :kneeling_woman: | `:kneeling_woman:` | :person_with_probing_cane: | `:person_with_probing_cane:` |
| :man_with_probing_cane: | `:man_with_probing_cane:` | :woman_with_probing_cane: | `:woman_with_probing_cane:` |
| :person_in_motorized_wheelchair: | `:person_in_motorized_wheelchair:` | :man_in_motorized_wheelchair: | `:man_in_motorized_wheelchair:` |
| :woman_in_motorized_wheelchair: | `:woman_in_motorized_wheelchair:` | :person_in_manual_wheelchair: | `:person_in_manual_wheelchair:` |
| :man_in_manual_wheelchair: | `:man_in_manual_wheelchair:` | :woman_in_manual_wheelchair: | `:woman_in_manual_wheelchair:` |
| :runner: | `:runner:` <br /> `:running:` | :running_man: | `:running_man:` |
| :running_woman: | `:running_woman:` | :dancer: | `:dancer:` <br /> `:woman_dancing:` |
| :man_dancing: | `:man_dancing:` | :business_suit_levitating: | `:business_suit_levitating:` |
| :dancers: | `:dancers:` | :dancing_men: | `:dancing_men:` |
| :dancing_women: | `:dancing_women:` | :sauna_person: | `:sauna_person:` |
| :sauna_man: | `:sauna_man:` | :sauna_woman: | `:sauna_woman:` |
| :climbing: | `:climbing:` | :climbing_man: | `:climbing_man:` |
| :climbing_woman: | `:climbing_woman:` | | |

#### Person Sport

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :person_fencing: | `:person_fencing:` | :horse_racing: | `:horse_racing:` |
| :skier: | `:skier:` | :snowboarder: | `:snowboarder:` |
| :golfing: | `:golfing:` | :golfing_man: | `:golfing_man:` |
| :golfing_woman: | `:golfing_woman:` | :surfer: | `:surfer:` |
| :surfing_man: | `:surfing_man:` | :surfing_woman: | `:surfing_woman:` |
| :rowboat: | `:rowboat:` | :rowing_man: | `:rowing_man:` |
| :rowing_woman: | `:rowing_woman:` | :swimmer: | `:swimmer:` |
| :swimming_man: | `:swimming_man:` | :swimming_woman: | `:swimming_woman:` |
| :bouncing_ball_person: | `:bouncing_ball_person:` | :basketball_man: | `:basketball_man:` <br /> `:bouncing_ball_man:` |
| :basketball_woman: | `:basketball_woman:` <br /> `:bouncing_ball_woman:` | :weight_lifting: | `:weight_lifting:` |
| :weight_lifting_man: | `:weight_lifting_man:` | :weight_lifting_woman: | `:weight_lifting_woman:` |
| :bicyclist: | `:bicyclist:` | :biking_man: | `:biking_man:` |
| :biking_woman: | `:biking_woman:` | :mountain_bicyclist: | `:mountain_bicyclist:` |
| :mountain_biking_man: | `:mountain_biking_man:` | :mountain_biking_woman: | `:mountain_biking_woman:` |
| :cartwheeling: | `:cartwheeling:` | :man_cartwheeling: | `:man_cartwheeling:` |
| :woman_cartwheeling: | `:woman_cartwheeling:` | :wrestling: | `:wrestling:` |
| :men_wrestling: | `:men_wrestling:` | :women_wrestling: | `:women_wrestling:` |
| :water_polo: | `:water_polo:` | :man_playing_water_polo: | `:man_playing_water_polo:` |
| :woman_playing_water_polo: | `:woman_playing_water_polo:` | :handball_person: | `:handball_person:` |
| :man_playing_handball: | `:man_playing_handball:` | :woman_playing_handball: | `:woman_playing_handball:` |
| :juggling_person: | `:juggling_person:` | :man_juggling: | `:man_juggling:` |
| :woman_juggling: | `:woman_juggling:` | | |

#### Person Resting

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :lotus_position: | `:lotus_position:` | :lotus_position_man: | `:lotus_position_man:` |
| :lotus_position_woman: | `:lotus_position_woman:` | :bath: | `:bath:` |
| :sleeping_bed: | `:sleeping_bed:` | | |

#### Family

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :people_holding_hands: | `:people_holding_hands:` | :two_women_holding_hands: | `:two_women_holding_hands:` |
| :couple: | `:couple:` | :two_men_holding_hands: | `:two_men_holding_hands:` |
| :couplekiss: | `:couplekiss:` | :couplekiss_man_woman: | `:couplekiss_man_woman:` |
| :couplekiss_man_man: | `:couplekiss_man_man:` | :couplekiss_woman_woman: | `:couplekiss_woman_woman:` |
| :couple_with_heart: | `:couple_with_heart:` | :couple_with_heart_woman_man: | `:couple_with_heart_woman_man:` |
| :couple_with_heart_man_man: | `:couple_with_heart_man_man:` | :couple_with_heart_woman_woman: | `:couple_with_heart_woman_woman:` |
| :family: | `:family:` | :family_man_woman_boy: | `:family_man_woman_boy:` |
| :family_man_woman_girl: | `:family_man_woman_girl:` | :family_man_woman_girl_boy: | `:family_man_woman_girl_boy:` |
| :family_man_woman_boy_boy: | `:family_man_woman_boy_boy:` | :family_man_woman_girl_girl: | `:family_man_woman_girl_girl:` |
| :family_man_man_boy: | `:family_man_man_boy:` | :family_man_man_girl: | `:family_man_man_girl:` |
| :family_man_man_girl_boy: | `:family_man_man_girl_boy:` | :family_man_man_boy_boy: | `:family_man_man_boy_boy:` |
| :family_man_man_girl_girl: | `:family_man_man_girl_girl:` | :family_woman_woman_boy: | `:family_woman_woman_boy:` |
| :family_woman_woman_girl: | `:family_woman_woman_girl:` | :family_woman_woman_girl_boy: | `:family_woman_woman_girl_boy:` |
| :family_woman_woman_boy_boy: | `:family_woman_woman_boy_boy:` | :family_woman_woman_girl_girl: | `:family_woman_woman_girl_girl:` |
| :family_man_boy: | `:family_man_boy:` | :family_man_boy_boy: | `:family_man_boy_boy:` |
| :family_man_girl: | `:family_man_girl:` | :family_man_girl_boy: | `:family_man_girl_boy:` |
| :family_man_girl_girl: | `:family_man_girl_girl:` | :family_woman_boy: | `:family_woman_boy:` |
| :family_woman_boy_boy: | `:family_woman_boy_boy:` | :family_woman_girl: | `:family_woman_girl:` |
| :family_woman_girl_boy: | `:family_woman_girl_boy:` | :family_woman_girl_girl: | `:family_woman_girl_girl:` |

#### Person Symbol

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :speaking_head: | `:speaking_head:` | :bust_in_silhouette: | `:bust_in_silhouette:` |
| :busts_in_silhouette: | `:busts_in_silhouette:` | :people_hugging: | `:people_hugging:` |
| :footprints: | `:footprints:` | | |

### 动物和自然 :dog:

#### Animal Mammal

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :monkey_face: | `:monkey_face:` | :monkey: | `:monkey:` |
| :gorilla: | `:gorilla:` | :orangutan: | `:orangutan:` |
| :dog: | `:dog:` | :dog2: | `:dog2:` |
| :guide_dog: | `:guide_dog:` | :service_dog: | `:service_dog:` |
| :poodle: | `:poodle:` | :wolf: | `:wolf:` |
| :fox_face: | `:fox_face:` | :raccoon: | `:raccoon:` |
| :cat: | `:cat:` | :cat2: | `:cat2:` |
| :black_cat: | `:black_cat:` | :lion: | `:lion:` |
| :tiger: | `:tiger:` | :tiger2: | `:tiger2:` |
| :leopard: | `:leopard:` | :horse: | `:horse:` |
| :racehorse: | `:racehorse:` | :unicorn: | `:unicorn:` |
| :zebra: | `:zebra:` | :deer: | `:deer:` |
| :bison: | `:bison:` | :cow: | `:cow:` |
| :ox: | `:ox:` | :water_buffalo: | `:water_buffalo:` |
| :cow2: | `:cow2:` | :pig: | `:pig:` |
| :pig2: | `:pig2:` | :boar: | `:boar:` |
| :pig_nose: | `:pig_nose:` | :ram: | `:ram:` |
| :sheep: | `:sheep:` | :goat: | `:goat:` |
| :dromedary_camel: | `:dromedary_camel:` | :camel: | `:camel:` |
| :llama: | `:llama:` | :giraffe: | `:giraffe:` |
| :elephant: | `:elephant:` | :mammoth: | `:mammoth:` |
| :rhinoceros: | `:rhinoceros:` | :hippopotamus: | `:hippopotamus:` |
| :mouse: | `:mouse:` | :mouse2: | `:mouse2:` |
| :rat: | `:rat:` | :hamster: | `:hamster:` |
| :rabbit: | `:rabbit:` | :rabbit2: | `:rabbit2:` |
| :chipmunk: | `:chipmunk:` | :beaver: | `:beaver:` |
| :hedgehog: | `:hedgehog:` | :bat: | `:bat:` |
| :bear: | `:bear:` | :polar_bear: | `:polar_bear:` |
| :koala: | `:koala:` | :panda_face: | `:panda_face:` |
| :sloth: | `:sloth:` | :otter: | `:otter:` |
| :skunk: | `:skunk:` | :kangaroo: | `:kangaroo:` |
| :badger: | `:badger:` | :feet: | `:feet:` <br /> `:paw_prints:` |

#### Animal Bird

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :turkey: | `:turkey:` | :chicken: | `:chicken:` |
| :rooster: | `:rooster:` | :hatching_chick: | `:hatching_chick:` |
| :baby_chick: | `:baby_chick:` | :hatched_chick: | `:hatched_chick:` |
| :bird: | `:bird:` | :penguin: | `:penguin:` |
| :dove: | `:dove:` | :eagle: | `:eagle:` |
| :duck: | `:duck:` | :swan: | `:swan:` |
| :owl: | `:owl:` | :dodo: | `:dodo:` |
| :feather: | `:feather:` | :flamingo: | `:flamingo:` |
| :peacock: | `:peacock:` | :parrot: | `:parrot:` |

#### Animal Amphibian

| ico | shortcode |
| - | :-: |
| :frog: | `:frog:` |

#### Animal Reptile

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :crocodile: | `:crocodile:` | :turtle: | `:turtle:` |
| :lizard: | `:lizard:` | :snake: | `:snake:` |
| :dragon_face: | `:dragon_face:` | :dragon: | `:dragon:` |
| :sauropod: | `:sauropod:` | :t-rex: | `:t-rex:` |

#### Animal Marine

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :whale: | `:whale:` | :whale2: | `:whale2:` |
| :dolphin: | `:dolphin:` <br /> `:flipper:` | :seal: | `:seal:` |
| :fish: | `:fish:` | :tropical_fish: | `:tropical_fish:` |
| :blowfish: | `:blowfish:` | :shark: | `:shark:` |
| :octopus: | `:octopus:` | :shell: | `:shell:` |

#### Animal Bug

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :snail: | `:snail:` | :butterfly: | `:butterfly:` |
| :bug: | `:bug:` | :ant: | `:ant:` |
| :bee: | `:bee:` <br /> `:honeybee:` | :beetle: | `:beetle:` |
| :lady_beetle: | `:lady_beetle:` | :cricket: | `:cricket:` |
| :cockroach: | `:cockroach:` | :spider: | `:spider:` |
| :spider_web: | `:spider_web:` | :scorpion: | `:scorpion:` |
| :mosquito: | `:mosquito:` | :fly: | `:fly:` |
| :worm: | `:worm:` | :microbe: | `:microbe:` |

#### Plant Flower

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :bouquet: | `:bouquet:` | :cherry_blossom: | `:cherry_blossom:` |
| :white_flower: | `:white_flower:` | :rosette: | `:rosette:` |
| :rose: | `:rose:` | :wilted_flower: | `:wilted_flower:` |
| :hibiscus: | `:hibiscus:` | :sunflower: | `:sunflower:` |
| :blossom: | `:blossom:` | :tulip: | `:tulip:` |

#### Plant Other

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :seedling: | `:seedling:` | :potted_plant: | `:potted_plant:` |
| :evergreen_tree: | `:evergreen_tree:` | :deciduous_tree: | `:deciduous_tree:` |
| :palm_tree: | `:palm_tree:` | :cactus: | `:cactus:` |
| :ear_of_rice: | `:ear_of_rice:` | :herb: | `:herb:` |
| :shamrock: | `:shamrock:` | :four_leaf_clover: | `:four_leaf_clover:` |
| :maple_leaf: | `:maple_leaf:` | :fallen_leaf: | `:fallen_leaf:` |
| :leaves: | `:leaves:` | | |

### 食物和饮料 :lemon:

#### Food Fruit

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :grapes: | `:grapes:` | :melon: | `:melon:` |
| :watermelon: | `:watermelon:` | :mandarin: | `:mandarin:` <br /> `:orange:` <br /> `:tangerine:` |
| :lemon: | `:lemon:` | :banana: | `:banana:` |
| :pineapple: | `:pineapple:` | :mango: | `:mango:` |
| :apple: | `:apple:` | :green_apple: | `:green_apple:` |
| :pear: | `:pear:` | :peach: | `:peach:` |
| :cherries: | `:cherries:` | :strawberry: | `:strawberry:` |
| :blueberries: | `:blueberries:` | :kiwi_fruit: | `:kiwi_fruit:` |
| :tomato: | `:tomato:` | :olive: | `:olive:` |
| :coconut: | `:coconut:` | | |

#### Food Vegetable

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :avocado: | `:avocado:` | :eggplant: | `:eggplant:` |
| :potato: | `:potato:` | :carrot: | `:carrot:` |
| :corn: | `:corn:` | :hot_pepper: | `:hot_pepper:` |
| :bell_pepper: | `:bell_pepper:` | :cucumber: | `:cucumber:` |
| :leafy_green: | `:leafy_green:` | :broccoli: | `:broccoli:` |
| :garlic: | `:garlic:` | :onion: | `:onion:` |
| :mushroom: | `:mushroom:` | :peanuts: | `:peanuts:` |
| :chestnut: | `:chestnut:` | | |

#### Food Prepared

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :bread: | `:bread:` | :croissant: | `:croissant:` |
| :baguette_bread: | `:baguette_bread:` | :flatbread: | `:flatbread:` |
| :pretzel: | `:pretzel:` | :bagel: | `:bagel:` |
| :pancakes: | `:pancakes:` | :waffle: | `:waffle:` |
| :cheese: | `:cheese:` | :meat_on_bone: | `:meat_on_bone:` |
| :poultry_leg: | `:poultry_leg:` | :cut_of_meat: | `:cut_of_meat:` |
| :bacon: | `:bacon:` | :hamburger: | `:hamburger:` |
| :fries: | `:fries:` | :pizza: | `:pizza:` |
| :hotdog: | `:hotdog:` | :sandwich: | `:sandwich:` |
| :taco: | `:taco:` | :burrito: | `:burrito:` |
| :tamale: | `:tamale:` | :stuffed_flatbread: | `:stuffed_flatbread:` |
| :falafel: | `:falafel:` | :egg: | `:egg:` |
| :fried_egg: | `:fried_egg:` | :shallow_pan_of_food: | `:shallow_pan_of_food:` |
| :stew: | `:stew:` | :fondue: | `:fondue:` |
| :bowl_with_spoon: | `:bowl_with_spoon:` | :green_salad: | `:green_salad:` |
| :popcorn: | `:popcorn:` | :butter: | `:butter:` |
| :salt: | `:salt:` | :canned_food: | `:canned_food:` |

#### Food Asian

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :bento: | `:bento:` | :rice_cracker: | `:rice_cracker:` |
| :rice_ball: | `:rice_ball:` | :rice: | `:rice:` |
| :curry: | `:curry:` | :ramen: | `:ramen:` |
| :spaghetti: | `:spaghetti:` | :sweet_potato: | `:sweet_potato:` |
| :oden: | `:oden:` | :sushi: | `:sushi:` |
| :fried_shrimp: | `:fried_shrimp:` | :fish_cake: | `:fish_cake:` |
| :moon_cake: | `:moon_cake:` | :dango: | `:dango:` |
| :dumpling: | `:dumpling:` | :fortune_cookie: | `:fortune_cookie:` |
| :takeout_box: | `:takeout_box:` | | |

#### Food Marine

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :crab: | `:crab:` | :lobster: | `:lobster:` |
| :shrimp: | `:shrimp:` | :squid: | `:squid:` |
| :oyster: | `:oyster:` | | |

#### Food Sweet

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :icecream: | `:icecream:` | :shaved_ice: | `:shaved_ice:` |
| :ice_cream: | `:ice_cream:` | :doughnut: | `:doughnut:` |
| :cookie: | `:cookie:` | :birthday: | `:birthday:` |
| :cake: | `:cake:` | :cupcake: | `:cupcake:` |
| :pie: | `:pie:` | :chocolate_bar: | `:chocolate_bar:` |
| :candy: | `:candy:` | :lollipop: | `:lollipop:` |
| :custard: | `:custard:` | :honey_pot: | `:honey_pot:` |

#### Drink

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :baby_bottle: | `:baby_bottle:` | :milk_glass: | `:milk_glass:` |
| :coffee: | `:coffee:` | :teapot: | `:teapot:` |
| :tea: | `:tea:` | :sake: | `:sake:` |
| :champagne: | `:champagne:` | :wine_glass: | `:wine_glass:` |
| :cocktail: | `:cocktail:` | :tropical_drink: | `:tropical_drink:` |
| :beer: | `:beer:` | :beers: | `:beers:` |
| :clinking_glasses: | `:clinking_glasses:` | :tumbler_glass: | `:tumbler_glass:` |
| :cup_with_straw: | `:cup_with_straw:` | :bubble_tea: | `:bubble_tea:` |
| :beverage_box: | `:beverage_box:` | :mate: | `:mate:` |
| :ice_cube: | `:ice_cube:` | | |

#### Dishware

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :chopsticks: | `:chopsticks:` | :plate_with_cutlery: | `:plate_with_cutlery:` |
| :fork_and_knife: | `:fork_and_knife:` | :spoon: | `:spoon:` |
| :hocho: | `:hocho:` <br /> `:knife:` | :amphora: | `:amphora:` |

### 旅行和地点 :rocket:

#### Place Map

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :earth_africa: | `:earth_africa:` | :earth_americas: | `:earth_americas:` |
| :earth_asia: | `:earth_asia:` | :globe_with_meridians: | `:globe_with_meridians:` |
| :world_map: | `:world_map:` | :japan: | `:japan:` |
| :compass: | `:compass:` | | |

#### Place Geographic

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :mountain_snow: | `:mountain_snow:` | :mountain: | `:mountain:` |
| :volcano: | `:volcano:` | :mount_fuji: | `:mount_fuji:` |
| :camping: | `:camping:` | :beach_umbrella: | `:beach_umbrella:` |
| :desert: | `:desert:` | :desert_island: | `:desert_island:` |
| :national_park: | `:national_park:` | | |

#### Place Building

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :stadium: | `:stadium:` | :classical_building: | `:classical_building:` |
| :building_construction: | `:building_construction:` | :bricks: | `:bricks:` |
| :rock: | `:rock:` | :wood: | `:wood:` |
| :hut: | `:hut:` | :houses: | `:houses:` |
| :derelict_house: | `:derelict_house:` | :house: | `:house:` |
| :house_with_garden: | `:house_with_garden:` | :office: | `:office:` |
| :post_office: | `:post_office:` | :european_post_office: | `:european_post_office:` |
| :hospital: | `:hospital:` | :bank: | `:bank:` |
| :hotel: | `:hotel:` | :love_hotel: | `:love_hotel:` |
| :convenience_store: | `:convenience_store:` | :school: | `:school:` |
| :department_store: | `:department_store:` | :factory: | `:factory:` |
| :japanese_castle: | `:japanese_castle:` | :european_castle: | `:european_castle:` |
| :wedding: | `:wedding:` | :tokyo_tower: | `:tokyo_tower:` |
| :statue_of_liberty: | `:statue_of_liberty:` | | |

#### Place Religious

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :church: | `:church:` | :mosque: | `:mosque:` |
| :hindu_temple: | `:hindu_temple:` | :synagogue: | `:synagogue:` |
| :shinto_shrine: | `:shinto_shrine:` | :kaaba: | `:kaaba:` |

#### Place Other

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :fountain: | `:fountain:` | :tent: | `:tent:` |
| :foggy: | `:foggy:` | :night_with_stars: | `:night_with_stars:` |
| :cityscape: | `:cityscape:` | :sunrise_over_mountains: | `:sunrise_over_mountains:` |
| :sunrise: | `:sunrise:` | :city_sunset: | `:city_sunset:` |
| :city_sunrise: | `:city_sunrise:` | :bridge_at_night: | `:bridge_at_night:` |
| :hotsprings: | `:hotsprings:` | :carousel_horse: | `:carousel_horse:` |
| :ferris_wheel: | `:ferris_wheel:` | :roller_coaster: | `:roller_coaster:` |
| :barber: | `:barber:` | :circus_tent: | `:circus_tent:` |

#### Transport Ground

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :steam_locomotive: | `:steam_locomotive:` | :railway_car: | `:railway_car:` |
| :bullettrain_side: | `:bullettrain_side:` | :bullettrain_front: | `:bullettrain_front:` |
| :train2: | `:train2:` | :metro: | `:metro:` |
| :light_rail: | `:light_rail:` | :station: | `:station:` |
| :tram: | `:tram:` | :monorail: | `:monorail:` |
| :mountain_railway: | `:mountain_railway:` | :train: | `:train:` |
| :bus: | `:bus:` | :oncoming_bus: | `:oncoming_bus:` |
| :trolleybus: | `:trolleybus:` | :minibus: | `:minibus:` |
| :ambulance: | `:ambulance:` | :fire_engine: | `:fire_engine:` |
| :police_car: | `:police_car:` | :oncoming_police_car: | `:oncoming_police_car:` |
| :taxi: | `:taxi:` | :oncoming_taxi: | `:oncoming_taxi:` |
| :car: | `:car:` <br /> `:red_car:` | :oncoming_automobile: | `:oncoming_automobile:` |
| :blue_car: | `:blue_car:` | :pickup_truck: | `:pickup_truck:` |
| :truck: | `:truck:` | :articulated_lorry: | `:articulated_lorry:` |
| :tractor: | `:tractor:` | :racing_car: | `:racing_car:` |
| :motorcycle: | `:motorcycle:` | :motor_scooter: | `:motor_scooter:` |
| :manual_wheelchair: | `:manual_wheelchair:` | :motorized_wheelchair: | `:motorized_wheelchair:` |
| :auto_rickshaw: | `:auto_rickshaw:` | :bike: | `:bike:` |
| :kick_scooter: | `:kick_scooter:` | :skateboard: | `:skateboard:` |
| :roller_skate: | `:roller_skate:` | :busstop: | `:busstop:` |
| :motorway: | `:motorway:` | :railway_track: | `:railway_track:` |
| :oil_drum: | `:oil_drum:` | :fuelpump: | `:fuelpump:` |
| :rotating_light: | `:rotating_light:` | :traffic_light: | `:traffic_light:` |
| :vertical_traffic_light: | `:vertical_traffic_light:` | :stop_sign: | `:stop_sign:` |
| :construction: | `:construction:` | | |

#### Transport Water

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :anchor: | `:anchor:` | :boat: | `:boat:` <br /> `:sailboat:` |
| :canoe: | `:canoe:` | :speedboat: | `:speedboat:` |
| :passenger_ship: | `:passenger_ship:` | :ferry: | `:ferry:` |
| :motor_boat: | `:motor_boat:` | :ship: | `:ship:` |

#### Transport Air

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :airplane: | `:airplane:` | :small_airplane: | `:small_airplane:` |
| :flight_departure: | `:flight_departure:` | :flight_arrival: | `:flight_arrival:` |
| :parachute: | `:parachute:` | :seat: | `:seat:` |
| :helicopter: | `:helicopter:` | :suspension_railway: | `:suspension_railway:` |
| :mountain_cableway: | `:mountain_cableway:` | :aerial_tramway: | `:aerial_tramway:` |
| :artificial_satellite: | `:artificial_satellite:` | :rocket: | `:rocket:` |
| :flying_saucer: | `:flying_saucer:` | | |

#### Hotel

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :bellhop_bell: | `:bellhop_bell:` | :luggage: | `:luggage:` |

#### Time

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :hourglass: | `:hourglass:` | :hourglass_flowing_sand: | `:hourglass_flowing_sand:` |
| :watch: | `:watch:` | :alarm_clock: | `:alarm_clock:` |
| :stopwatch: | `:stopwatch:` | :timer_clock: | `:timer_clock:` |
| :mantelpiece_clock: | `:mantelpiece_clock:` | :clock12: | `:clock12:` |
| :clock1230: | `:clock1230:` | :clock1: | `:clock1:` |
| :clock130: | `:clock130:` | :clock2: | `:clock2:` |
| :clock230: | `:clock230:` | :clock3: | `:clock3:` |
| :clock330: | `:clock330:` | :clock4: | `:clock4:` |
| :clock430: | `:clock430:` | :clock5: | `:clock5:` |
| :clock530: | `:clock530:` | :clock6: | `:clock6:` |
| :clock630: | `:clock630:` | :clock7: | `:clock7:` |
| :clock730: | `:clock730:` | :clock8: | `:clock8:` |
| :clock830: | `:clock830:` | :clock9: | `:clock9:` |
| :clock930: | `:clock930:` | :clock10: | `:clock10:` |
| :clock1030: | `:clock1030:` | :clock11: | `:clock11:` |
| :clock1130: | `:clock1130:` | | |

#### Sky & Weather

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :new_moon: | `:new_moon:` | :waxing_crescent_moon: | `:waxing_crescent_moon:` |
| :first_quarter_moon: | `:first_quarter_moon:` | :moon: | `:moon:` <br /> `:waxing_gibbous_moon:` |
| :full_moon: | `:full_moon:` | :waning_gibbous_moon: | `:waning_gibbous_moon:` |
| :last_quarter_moon: | `:last_quarter_moon:` | :waning_crescent_moon: | `:waning_crescent_moon:` |
| :crescent_moon: | `:crescent_moon:` | :new_moon_with_face: | `:new_moon_with_face:` |
| :first_quarter_moon_with_face: | `:first_quarter_moon_with_face:` | :last_quarter_moon_with_face: | `:last_quarter_moon_with_face:` |
| :thermometer: | `:thermometer:` | :sunny: | `:sunny:` |
| :full_moon_with_face: | `:full_moon_with_face:` | :sun_with_face: | `:sun_with_face:` |
| :ringed_planet: | `:ringed_planet:` | :star: | `:star:` |
| :star2: | `:star2:` | :stars: | `:stars:` |
| :milky_way: | `:milky_way:` | :cloud: | `:cloud:` |
| :partly_sunny: | `:partly_sunny:` | :cloud_with_lightning_and_rain: | `:cloud_with_lightning_and_rain:` |
| :sun_behind_small_cloud: | `:sun_behind_small_cloud:` | :sun_behind_large_cloud: | `:sun_behind_large_cloud:` |
| :sun_behind_rain_cloud: | `:sun_behind_rain_cloud:` | :cloud_with_rain: | `:cloud_with_rain:` |
| :cloud_with_snow: | `:cloud_with_snow:` | :cloud_with_lightning: | `:cloud_with_lightning:` |
| :tornado: | `:tornado:` | :fog: | `:fog:` |
| :wind_face: | `:wind_face:` | :cyclone: | `:cyclone:` |
| :rainbow: | `:rainbow:` | :closed_umbrella: | `:closed_umbrella:` |
| :open_umbrella: | `:open_umbrella:` | :umbrella: | `:umbrella:` |
| :parasol_on_ground: | `:parasol_on_ground:` | :zap: | `:zap:` |
| :snowflake: | `:snowflake:` | :snowman_with_snow: | `:snowman_with_snow:` |
| :snowman: | `:snowman:` | :comet: | `:comet:` |
| :fire: | `:fire:` | :droplet: | `:droplet:` |
| :ocean: | `:ocean:` | | |

### 活动 :tada:

#### Event

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :jack_o_lantern: | `:jack_o_lantern:` | :christmas_tree: | `:christmas_tree:` |
| :fireworks: | `:fireworks:` | :sparkler: | `:sparkler:` |
| :firecracker: | `:firecracker:` | :sparkles: | `:sparkles:` |
| :balloon: | `:balloon:` | :tada: | `:tada:` |
| :confetti_ball: | `:confetti_ball:` | :tanabata_tree: | `:tanabata_tree:` |
| :bamboo: | `:bamboo:` | :dolls: | `:dolls:` |
| :flags: | `:flags:` | :wind_chime: | `:wind_chime:` |
| :rice_scene: | `:rice_scene:` | :red_envelope: | `:red_envelope:` |
| :ribbon: | `:ribbon:` | :gift: | `:gift:` |
| :reminder_ribbon: | `:reminder_ribbon:` | :tickets: | `:tickets:` |
| :ticket: | `:ticket:` | | |

#### Award Medal

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :medal_military: | `:medal_military:` | :trophy: | `:trophy:` |
| :medal_sports: | `:medal_sports:` | :1st_place_medal: | `:1st_place_medal:` |
| :2nd_place_medal: | `:2nd_place_medal:` | :3rd_place_medal: | `:3rd_place_medal:` |

#### Sport

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :soccer: | `:soccer:` | :baseball: | `:baseball:` |
| :softball: | `:softball:` | :basketball: | `:basketball:` |
| :volleyball: | `:volleyball:` | :football: | `:football:` |
| :rugby_football: | `:rugby_football:` | :tennis: | `:tennis:` |
| :flying_disc: | `:flying_disc:` | :bowling: | `:bowling:` |
| :cricket_game: | `:cricket_game:` | :field_hockey: | `:field_hockey:` |
| :ice_hockey: | `:ice_hockey:` | :lacrosse: | `:lacrosse:` |
| :ping_pong: | `:ping_pong:` | :badminton: | `:badminton:` |
| :boxing_glove: | `:boxing_glove:` | :martial_arts_uniform: | `:martial_arts_uniform:` |
| :goal_net: | `:goal_net:` | :golf: | `:golf:` |
| :ice_skate: | `:ice_skate:` | :fishing_pole_and_fish: | `:fishing_pole_and_fish:` |
| :diving_mask: | `:diving_mask:` | :running_shirt_with_sash: | `:running_shirt_with_sash:` |
| :ski: | `:ski:` | :sled: | `:sled:` |
| :curling_stone: | `:curling_stone:` | | |

#### Game

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :dart: | `:dart:` | :yo_yo: | `:yo_yo:` |
| :kite: | `:kite:` | :8ball: | `:8ball:` |
| :crystal_ball: | `:crystal_ball:` | :magic_wand: | `:magic_wand:` |
| :nazar_amulet: | `:nazar_amulet:` | :video_game: | `:video_game:` |
| :joystick: | `:joystick:` | :slot_machine: | `:slot_machine:` |
| :game_die: | `:game_die:` | :jigsaw: | `:jigsaw:` |
| :teddy_bear: | `:teddy_bear:` | :pinata: | `:pinata:` |
| :nesting_dolls: | `:nesting_dolls:` | :spades: | `:spades:` |
| :hearts: | `:hearts:` | :diamonds: | `:diamonds:` |
| :clubs: | `:clubs:` | :chess_pawn: | `:chess_pawn:` |
| :black_joker: | `:black_joker:` | :mahjong: | `:mahjong:` |
| :flower_playing_cards: | `:flower_playing_cards:` | | |

#### Arts & Crafts

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :performing_arts: | `:performing_arts:` | :framed_picture: | `:framed_picture:` |
| :art: | `:art:` | :thread: | `:thread:` |
| :sewing_needle: | `:sewing_needle:` | :yarn: | `:yarn:` |
| :knot: | `:knot:` | | |

### 物件 :bikini:

#### Clothing

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :eyeglasses: | `:eyeglasses:` | :dark_sunglasses: | `:dark_sunglasses:` |
| :goggles: | `:goggles:` | :lab_coat: | `:lab_coat:` |
| :safety_vest: | `:safety_vest:` | :necktie: | `:necktie:` |
| :shirt: | `:shirt:` <br /> `:tshirt:` | :jeans: | `:jeans:` |
| :scarf: | `:scarf:` | :gloves: | `:gloves:` |
| :coat: | `:coat:` | :socks: | `:socks:` |
| :dress: | `:dress:` | :kimono: | `:kimono:` |
| :sari: | `:sari:` | :one_piece_swimsuit: | `:one_piece_swimsuit:` |
| :swim_brief: | `:swim_brief:` | :shorts: | `:shorts:` |
| :bikini: | `:bikini:` | :womans_clothes: | `:womans_clothes:` |
| :purse: | `:purse:` | :handbag: | `:handbag:` |
| :pouch: | `:pouch:` | :shopping: | `:shopping:` |
| :school_satchel: | `:school_satchel:` | :thong_sandal: | `:thong_sandal:` |
| :mans_shoe: | `:mans_shoe:` <br /> `:shoe:` | :athletic_shoe: | `:athletic_shoe:` |
| :hiking_boot: | `:hiking_boot:` | :flat_shoe: | `:flat_shoe:` |
| :high_heel: | `:high_heel:` | :sandal: | `:sandal:` |
| :ballet_shoes: | `:ballet_shoes:` | :boot: | `:boot:` |
| :crown: | `:crown:` | :womans_hat: | `:womans_hat:` |
| :tophat: | `:tophat:` | :mortar_board: | `:mortar_board:` |
| :billed_cap: | `:billed_cap:` | :military_helmet: | `:military_helmet:` |
| :rescue_worker_helmet: | `:rescue_worker_helmet:` | :prayer_beads: | `:prayer_beads:` |
| :lipstick: | `:lipstick:` | :ring: | `:ring:` |
| :gem: | `:gem:` | | |

#### Sound

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :mute: | `:mute:` | :speaker: | `:speaker:` |
| :sound: | `:sound:` | :loud_sound: | `:loud_sound:` |
| :loudspeaker: | `:loudspeaker:` | :mega: | `:mega:` |
| :postal_horn: | `:postal_horn:` | :bell: | `:bell:` |
| :no_bell: | `:no_bell:` | | |

#### Music

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :musical_score: | `:musical_score:` | :musical_note: | `:musical_note:` |
| :notes: | `:notes:` | :studio_microphone: | `:studio_microphone:` |
| :level_slider: | `:level_slider:` | :control_knobs: | `:control_knobs:` |
| :microphone: | `:microphone:` | :headphones: | `:headphones:` |
| :radio: | `:radio:` | | |

#### Musical Instrument

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :saxophone: | `:saxophone:` | :accordion: | `:accordion:` |
| :guitar: | `:guitar:` | :musical_keyboard: | `:musical_keyboard:` |
| :trumpet: | `:trumpet:` | :violin: | `:violin:` |
| :banjo: | `:banjo:` | :drum: | `:drum:` |
| :long_drum: | `:long_drum:` | | |

#### Phone

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :iphone: | `:iphone:` | :calling: | `:calling:` |
| :phone: | `:phone:` <br /> `:telephone:` | :telephone_receiver: | `:telephone_receiver:` |
| :pager: | `:pager:` | :fax: | `:fax:` |

#### Computer

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :battery: | `:battery:` | :electric_plug: | `:electric_plug:` |
| :computer: | `:computer:` | :desktop_computer: | `:desktop_computer:` |
| :printer: | `:printer:` | :keyboard: | `:keyboard:` |
| :computer_mouse: | `:computer_mouse:` | :trackball: | `:trackball:` |
| :minidisc: | `:minidisc:` | :floppy_disk: | `:floppy_disk:` |
| :cd: | `:cd:` | :dvd: | `:dvd:` |
| :abacus: | `:abacus:` | | |

#### Light & Video

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :movie_camera: | `:movie_camera:` | :film_strip: | `:film_strip:` |
| :film_projector: | `:film_projector:` | :clapper: | `:clapper:` |
| :tv: | `:tv:` | :camera: | `:camera:` |
| :camera_flash: | `:camera_flash:` | :video_camera: | `:video_camera:` |
| :vhs: | `:vhs:` | :mag: | `:mag:` |
| :mag_right: | `:mag_right:` | :candle: | `:candle:` |
| :bulb: | `:bulb:` | :flashlight: | `:flashlight:` |
| :izakaya_lantern: | `:izakaya_lantern:` <br /> `:lantern:` | :diya_lamp: | `:diya_lamp:` |

#### Book Paper

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :notebook_with_decorative_cover: | `:notebook_with_decorative_cover:` | :closed_book: | `:closed_book:` |
| :book: | `:book:` <br /> `:open_book:` | :green_book: | `:green_book:` |
| :blue_book: | `:blue_book:` | :orange_book: | `:orange_book:` |
| :books: | `:books:` | :notebook: | `:notebook:` |
| :ledger: | `:ledger:` | :page_with_curl: | `:page_with_curl:` |
| :scroll: | `:scroll:` | :page_facing_up: | `:page_facing_up:` |
| :newspaper: | `:newspaper:` | :newspaper_roll: | `:newspaper_roll:` |
| :bookmark_tabs: | `:bookmark_tabs:` | :bookmark: | `:bookmark:` |
| :label: | `:label:` | | |

#### Money

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :moneybag: | `:moneybag:` | :coin: | `:coin:` |
| :yen: | `:yen:` | :dollar: | `:dollar:` |
| :euro: | `:euro:` | :pound: | `:pound:` |
| :money_with_wings: | `:money_with_wings:` | :credit_card: | `:credit_card:` |
| :receipt: | `:receipt:` | :chart: | `:chart:` |

#### Mail

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :envelope: | `:envelope:` | :e-mail: | `:e-mail:` <br /> `:email:` |
| :incoming_envelope: | `:incoming_envelope:` | :envelope_with_arrow: | `:envelope_with_arrow:` |
| :outbox_tray: | `:outbox_tray:` | :inbox_tray: | `:inbox_tray:` |
| :package: | `:package:` | :mailbox: | `:mailbox:` |
| :mailbox_closed: | `:mailbox_closed:` | :mailbox_with_mail: | `:mailbox_with_mail:` |
| :mailbox_with_no_mail: | `:mailbox_with_no_mail:` | :postbox: | `:postbox:` |
| :ballot_box: | `:ballot_box:` | | |

#### Writing

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :pencil2: | `:pencil2:` | :black_nib: | `:black_nib:` |
| :fountain_pen: | `:fountain_pen:` | :pen: | `:pen:` |
| :paintbrush: | `:paintbrush:` | :crayon: | `:crayon:` |
| :memo: | `:memo:` <br /> `:pencil:` | | |

#### Office

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :briefcase: | `:briefcase:` | :file_folder: | `:file_folder:` |
| :open_file_folder: | `:open_file_folder:` | :card_index_dividers: | `:card_index_dividers:` |
| :date: | `:date:` | :calendar: | `:calendar:` |
| :spiral_notepad: | `:spiral_notepad:` | :spiral_calendar: | `:spiral_calendar:` |
| :card_index: | `:card_index:` | :chart_with_upwards_trend: | `:chart_with_upwards_trend:` |
| :chart_with_downwards_trend: | `:chart_with_downwards_trend:` | :bar_chart: | `:bar_chart:` |
| :clipboard: | `:clipboard:` | :pushpin: | `:pushpin:` |
| :round_pushpin: | `:round_pushpin:` | :paperclip: | `:paperclip:` |
| :paperclips: | `:paperclips:` | :straight_ruler: | `:straight_ruler:` |
| :triangular_ruler: | `:triangular_ruler:` | :scissors: | `:scissors:` |
| :card_file_box: | `:card_file_box:` | :file_cabinet: | `:file_cabinet:` |
| :wastebasket: | `:wastebasket:` | | |

#### Lock

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :lock: | `:lock:` | :unlock: | `:unlock:` |
| :lock_with_ink_pen: | `:lock_with_ink_pen:` | :closed_lock_with_key: | `:closed_lock_with_key:` |
| :key: | `:key:` | :old_key: | `:old_key:` |

#### Tool

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :hammer: | `:hammer:` | :axe: | `:axe:` |
| :pick: | `:pick:` | :hammer_and_pick: | `:hammer_and_pick:` |
| :hammer_and_wrench: | `:hammer_and_wrench:` | :dagger: | `:dagger:` |
| :crossed_swords: | `:crossed_swords:` | :gun: | `:gun:` |
| :boomerang: | `:boomerang:` | :bow_and_arrow: | `:bow_and_arrow:` |
| :shield: | `:shield:` | :carpentry_saw: | `:carpentry_saw:` |
| :wrench: | `:wrench:` | :screwdriver: | `:screwdriver:` |
| :nut_and_bolt: | `:nut_and_bolt:` | :gear: | `:gear:` |
| :clamp: | `:clamp:` | :balance_scale: | `:balance_scale:` |
| :probing_cane: | `:probing_cane:` | :link: | `:link:` |
| :chains: | `:chains:` | :hook: | `:hook:` |
| :toolbox: | `:toolbox:` | :magnet: | `:magnet:` |
| :ladder: | `:ladder:` | | |

#### Science

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :alembic: | `:alembic:` | :test_tube: | `:test_tube:` |
| :petri_dish: | `:petri_dish:` | :dna: | `:dna:` |
| :microscope: | `:microscope:` | :telescope: | `:telescope:` |
| :satellite: | `:satellite:` | | |

#### Medical

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :syringe: | `:syringe:` | :drop_of_blood: | `:drop_of_blood:` |
| :pill: | `:pill:` | :adhesive_bandage: | `:adhesive_bandage:` |
| :stethoscope: | `:stethoscope:` | | |

#### Household

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :door: | `:door:` | :elevator: | `:elevator:` |
| :mirror: | `:mirror:` | :window: | `:window:` |
| :bed: | `:bed:` | :couch_and_lamp: | `:couch_and_lamp:` |
| :chair: | `:chair:` | :toilet: | `:toilet:` |
| :plunger: | `:plunger:` | :shower: | `:shower:` |
| :bathtub: | `:bathtub:` | :mouse_trap: | `:mouse_trap:` |
| :razor: | `:razor:` | :lotion_bottle: | `:lotion_bottle:` |
| :safety_pin: | `:safety_pin:` | :broom: | `:broom:` |
| :basket: | `:basket:` | :roll_of_paper: | `:roll_of_paper:` |
| :bucket: | `:bucket:` | :soap: | `:soap:` |
| :toothbrush: | `:toothbrush:` | :sponge: | `:sponge:` |
| :fire_extinguisher: | `:fire_extinguisher:` | :shopping_cart: | `:shopping_cart:` |

#### Other Object

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :smoking: | `:smoking:` | :coffin: | `:coffin:` |
| :headstone: | `:headstone:` | :funeral_urn: | `:funeral_urn:` |
| :moyai: | `:moyai:` | :placard: | `:placard:` |

### 符号 :radioactive:

#### Transport Sign

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :atm: | `:atm:` | :put_litter_in_its_place: | `:put_litter_in_its_place:` |
| :potable_water: | `:potable_water:` | :wheelchair: | `:wheelchair:` |
| :mens: | `:mens:` | :womens: | `:womens:` |
| :restroom: | `:restroom:` | :baby_symbol: | `:baby_symbol:` |
| :wc: | `:wc:` | :passport_control: | `:passport_control:` |
| :customs: | `:customs:` | :baggage_claim: | `:baggage_claim:` |
| :left_luggage: | `:left_luggage:` | | |

#### Warning

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :warning: | `:warning:` | :children_crossing: | `:children_crossing:` |
| :no_entry: | `:no_entry:` | :no_entry_sign: | `:no_entry_sign:` |
| :no_bicycles: | `:no_bicycles:` | :no_smoking: | `:no_smoking:` |
| :do_not_litter: | `:do_not_litter:` | :non-potable_water: | `:non-potable_water:` |
| :no_pedestrians: | `:no_pedestrians:` | :no_mobile_phones: | `:no_mobile_phones:` |
| :underage: | `:underage:` | :radioactive: | `:radioactive:` |
| :biohazard: | `:biohazard:` | | |

#### Arrow

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :arrow_up: | `:arrow_up:` | :arrow_upper_right: | `:arrow_upper_right:` |
| :arrow_right: | `:arrow_right:` | :arrow_lower_right: | `:arrow_lower_right:` |
| :arrow_down: | `:arrow_down:` | :arrow_lower_left: | `:arrow_lower_left:` |
| :arrow_left: | `:arrow_left:` | :arrow_upper_left: | `:arrow_upper_left:` |
| :arrow_up_down: | `:arrow_up_down:` | :left_right_arrow: | `:left_right_arrow:` |
| :leftwards_arrow_with_hook: | `:leftwards_arrow_with_hook:` | :arrow_right_hook: | `:arrow_right_hook:` |
| :arrow_heading_up: | `:arrow_heading_up:` | :arrow_heading_down: | `:arrow_heading_down:` |
| :arrows_clockwise: | `:arrows_clockwise:` | :arrows_counterclockwise: | `:arrows_counterclockwise:` |
| :back: | `:back:` | :end: | `:end:` |
| :on: | `:on:` | :soon: | `:soon:` |
| :top: | `:top:` | | |

#### Religion

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :place_of_worship: | `:place_of_worship:` | :atom_symbol: | `:atom_symbol:` |
| :om: | `:om:` | :star_of_david: | `:star_of_david:` |
| :wheel_of_dharma: | `:wheel_of_dharma:` | :yin_yang: | `:yin_yang:` |
| :latin_cross: | `:latin_cross:` | :orthodox_cross: | `:orthodox_cross:` |
| :star_and_crescent: | `:star_and_crescent:` | :peace_symbol: | `:peace_symbol:` |
| :menorah: | `:menorah:` | :six_pointed_star: | `:six_pointed_star:` |

#### Zodiac

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :aries: | `:aries:` | :taurus: | `:taurus:` |
| :gemini: | `:gemini:` | :cancer: | `:cancer:` |
| :leo: | `:leo:` | :virgo: | `:virgo:` |
| :libra: | `:libra:` | :scorpius: | `:scorpius:` |
| :sagittarius: | `:sagittarius:` | :capricorn: | `:capricorn:` |
| :aquarius: | `:aquarius:` | :pisces: | `:pisces:` |
| :ophiuchus: | `:ophiuchus:` | | |

#### Av Symbol

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :twisted_rightwards_arrows: | `:twisted_rightwards_arrows:` | :repeat: | `:repeat:` |
| :repeat_one: | `:repeat_one:` | :arrow_forward: | `:arrow_forward:` |
| :fast_forward: | `:fast_forward:` | :next_track_button: | `:next_track_button:` |
| :play_or_pause_button: | `:play_or_pause_button:` | :arrow_backward: | `:arrow_backward:` |
| :rewind: | `:rewind:` | :previous_track_button: | `:previous_track_button:` |
| :arrow_up_small: | `:arrow_up_small:` | :arrow_double_up: | `:arrow_double_up:` |
| :arrow_down_small: | `:arrow_down_small:` | :arrow_double_down: | `:arrow_double_down:` |
| :pause_button: | `:pause_button:` | :stop_button: | `:stop_button:` |
| :record_button: | `:record_button:` | :eject_button: | `:eject_button:` |
| :cinema: | `:cinema:` | :low_brightness: | `:low_brightness:` |
| :high_brightness: | `:high_brightness:` | :signal_strength: | `:signal_strength:` |
| :vibration_mode: | `:vibration_mode:` | :mobile_phone_off: | `:mobile_phone_off:` |

#### Gender

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :female_sign: | `:female_sign:` | :male_sign: | `:male_sign:` |
| :transgender_symbol: | `:transgender_symbol:` | | |

#### Math

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :heavy_multiplication_x: | `:heavy_multiplication_x:` | :heavy_plus_sign: | `:heavy_plus_sign:` |
| :heavy_minus_sign: | `:heavy_minus_sign:` | :heavy_division_sign: | `:heavy_division_sign:` |
| :infinity: | `:infinity:` | | |

#### Punctuation

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :bangbang: | `:bangbang:` | :interrobang: | `:interrobang:` |
| :question: | `:question:` | :grey_question: | `:grey_question:` |
| :grey_exclamation: | `:grey_exclamation:` | :exclamation: | `:exclamation:` <br /> `:heavy_exclamation_mark:` |
| :wavy_dash: | `:wavy_dash:` | | |

#### Currency

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :currency_exchange: | `:currency_exchange:` | :heavy_dollar_sign: | `:heavy_dollar_sign:` |

#### Other Symbol

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :medical_symbol: | `:medical_symbol:` | :recycle: | `:recycle:` |
| :fleur_de_lis: | `:fleur_de_lis:` | :trident: | `:trident:` |
| :name_badge: | `:name_badge:` | :beginner: | `:beginner:` |
| :o: | `:o:` | :white_check_mark: | `:white_check_mark:` |
| :ballot_box_with_check: | `:ballot_box_with_check:` | :heavy_check_mark: | `:heavy_check_mark:` |
| :x: | `:x:` | :negative_squared_cross_mark: | `:negative_squared_cross_mark:` |
| :curly_loop: | `:curly_loop:` | :loop: | `:loop:` |
| :part_alternation_mark: | `:part_alternation_mark:` | :eight_spoked_asterisk: | `:eight_spoked_asterisk:` |
| :eight_pointed_black_star: | `:eight_pointed_black_star:` | :sparkle: | `:sparkle:` |
| :copyright: | `:copyright:` | :registered: | `:registered:` |
| :tm: | `:tm:` | | |

#### Keycap

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :hash: | `:hash:` | :asterisk: | `:asterisk:` |
| :zero: | `:zero:` | :one: | `:one:` |
| :two: | `:two:` | :three: | `:three:` |
| :four: | `:four:` | :five: | `:five:` |
| :six: | `:six:` | :seven: | `:seven:` |
| :eight: | `:eight:` | :nine: | `:nine:` |
| :keycap_ten: | `:keycap_ten:` | | |

#### Alphanum

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :capital_abcd: | `:capital_abcd:` | :abcd: | `:abcd:` |
| :1234: | `:1234:` | :symbols: | `:symbols:` |
| :abc: | `:abc:` | :a: | `:a:` |
| :ab: | `:ab:` | :b: | `:b:` |
| :cl: | `:cl:` | :cool: | `:cool:` |
| :free: | `:free:` | :information_source: | `:information_source:` |
| :id: | `:id:` | :m: | `:m:` |
| :new: | `:new:` | :ng: | `:ng:` |
| :o2: | `:o2:` | :ok: | `:ok:` |
| :parking: | `:parking:` | :sos: | `:sos:` |
| :up: | `:up:` | :vs: | `:vs:` |
| :koko: | `:koko:` | :sa: | `:sa:` |
| :u6708: | `:u6708:` | :u6709: | `:u6709:` |
| :u6307: | `:u6307:` | :ideograph_advantage: | `:ideograph_advantage:` |
| :u5272: | `:u5272:` | :u7121: | `:u7121:` |
| :u7981: | `:u7981:` | :accept: | `:accept:` |
| :u7533: | `:u7533:` | :u5408: | `:u5408:` |
| :u7a7a: | `:u7a7a:` | :congratulations: | `:congratulations:` |
| :secret: | `:secret:` | :u55b6: | `:u55b6:` |
| :u6e80: | `:u6e80:` | | |

#### Geometric

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :red_circle: | `:red_circle:` | :orange_circle: | `:orange_circle:` |
| :yellow_circle: | `:yellow_circle:` | :green_circle: | `:green_circle:` |
| :large_blue_circle: | `:large_blue_circle:` | :purple_circle: | `:purple_circle:` |
| :brown_circle: | `:brown_circle:` | :black_circle: | `:black_circle:` |
| :white_circle: | `:white_circle:` | :red_square: | `:red_square:` |
| :orange_square: | `:orange_square:` | :yellow_square: | `:yellow_square:` |
| :green_square: | `:green_square:` | :blue_square: | `:blue_square:` |
| :purple_square: | `:purple_square:` | :brown_square: | `:brown_square:` |
| :black_large_square: | `:black_large_square:` | :white_large_square: | `:white_large_square:` |
| :black_medium_square: | `:black_medium_square:` | :white_medium_square: | `:white_medium_square:` |
| :black_medium_small_square: | `:black_medium_small_square:` | :white_medium_small_square: | `:white_medium_small_square:` |
| :black_small_square: | `:black_small_square:` | :white_small_square: | `:white_small_square:` |
| :large_orange_diamond: | `:large_orange_diamond:` | :large_blue_diamond: | `:large_blue_diamond:` |
| :small_orange_diamond: | `:small_orange_diamond:` | :small_blue_diamond: | `:small_blue_diamond:` |
| :small_red_triangle: | `:small_red_triangle:` | :small_red_triangle_down: | `:small_red_triangle_down:` |
| :diamond_shape_with_a_dot_inside: | `:diamond_shape_with_a_dot_inside:` | :radio_button: | `:radio_button:` |
| :white_square_button: | `:white_square_button:` | :black_square_button: | `:black_square_button:` |

### 旗帜 :rainbow_flag:

#### Flag

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :checkered_flag: | `:checkered_flag:` | :triangular_flag_on_post: | `:triangular_flag_on_post:` |
| :crossed_flags: | `:crossed_flags:` | :black_flag: | `:black_flag:` |
| :white_flag: | `:white_flag:` | :rainbow_flag: | `:rainbow_flag:` |
| :transgender_flag: | `:transgender_flag:` | :pirate_flag: | `:pirate_flag:` |

#### Subdivision Flag

| ico | shortcode | ico | shortcode |
| :-: | - | :-: | - |
| :england: | `:england:` | :scotland: | `:scotland:` |
| :wales: | `:wales:` | | |