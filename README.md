<p align="center">
    <img src="logo.png" width="150"/>
<p>

  
# 👉🏻 QinYu: A Family of High-Fidelity Zero-Shot TTS with High Naturalness, Spontaneous Colloquialism, and Emotional Control 👈🏻 
<a href="http://tme-lyra-lab.github.io/" ><img src="https://img.shields.io/badge/Demo-Try%20Now-blue" alt="Demo"></a> | <a href="README_zh.md"><img src="https://img.shields.io/badge/语言-简体中文-green" alt="简体中文"></a>


## Highlight🔥  
QinYu is a breakthrough high-fidelity text-to-speech (TTS) system that redefines synthetic speech quality with 32kHz studio-grade audio, natural conversational flow, and precise emotional expression—surpassing the 22kHz limit of most open-source TTS systems.  


## Core Capabilities  
### Paralanguage Voice Generation  
Generates authentic paralinguistic elements like natural laughter and prosodic pauses, making synthetic speech indistinguishable from human conversation.  


### Instructed Voice Generation (QinYuInstruct)  
Enables fine-grained emotional control via natural language descriptions, with multi-speaker support for scenario-specific expression.  

*Key Features*:  
- Emotion specificity: "愤怒、质问", "无奈", "遗憾惋惜", "懊恼、关切"  
- Speaker diversity: Multiple unique voices with consistent timbre across emotions and texts.  


### Text-to-Timbre
[Demos](https://tme-lyra-lab.github.io/QinYu-AutoBook/)

Customizes voice timbre based on character attributes (age, gender, identity, personality), creating distinct vocal identities for diverse roles.  

*Categories*:  
- Child (e.g., "该角色是一个幼儿女性，身份是小郡主/公主，性格骄慢却善良、爱助人，气质高贵带娇憨。")  
- Youth (e.g., "该角色是一个青年女性，身份是医者/药师，性格温婉善良、细腻包容，气质清雅含蓄，音色柔和温暖，语速舒缓")  
- Middle-aged (e.g., "该角色是一个中年男性，身份是王朝将军，性格铁血威严、霸气侧漏，气质不怒自威")  
- Elderly (e.g., "该角色是一个老年男性，身份是退隐老帝/太上皇，性格深不可测、威势犹存，气质泰山压顶")  
- Non-human (e.g., "该角色是一个非人类树精（中年男性），身份是古木灵/山林守护者，性格沉稳寡言、爱自然，气质古老带绿意")  


### Podcast Generation (QinYuCast)  
Specialized for podcast scenarios, delivering natural conversational flow with colloquial artifacts that mimic real human dialogue.  

*Key Features*:  
- Spontaneous interaction: Automatically inserts natural pauses, filler words ("呃", "对吧"), and conversational cues.  
- Role differentiation: Maintains distinct voice characteristics for multiple speakers in dialogue.  
- Topic adaptation: Adjusts prosody to match content tone (e.g., analytical for music reviews, casual for daily chats).  

*Example*:  
- [S1] 哈喽大家好，欢迎收听今天的播客，咱们聊聊周杰伦的《止战之殇》啊。  
- [S2] 这歌我熟！创作背景特别有意义，是以海参崴的战后场景为原型的吧？  
- [S1] 对，而且MV里特意用了孩子的镜头，那种空洞的眼神特别打动人……  


### Scenario-Specific Variants  
- **QinYuCast**: Optimized for podcasts and conversational scenarios, automating colloquial artifacts like natural pauses, hesitations, and interjections.  
- **QinYuInstruct**: Tailored for narrative contexts (audiobooks, storytelling), enabling emotion specification via simple descriptions (e.g., "warm", "excited", "sorrowful").  


## Technical Advantages  
- **High Fidelity**: 32kHz audio resolution with rich spectral details, exceeding industry standards for clarity and naturalness.  
- **Zero-Shot Adaptability**: No fine-tuning required for new voices, emotions, or languages, enabling rapid deployment across use cases.  
- **Scalability**: Built on a million-hour-scale base model, with future "ALL-in-One" architecture planning to integrate controllable paralinguistic tagging, adjustable colloquialism strength, and novel voice generation.  


### BibTeX
```bibtex
@article{qinyu-2025,  
  title={QinYu: A Family of High-Fidelity Zero-Shot TTS with High Naturalness, Spontaneous Colloquialism, and Emotional Control},  
  author={QinYu Team, TME Lyra Lab},  
  year={2025}  
}
```
