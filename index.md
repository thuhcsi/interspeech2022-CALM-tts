---
layout: default
---
# Subjective Evaluation 
We use two datasets to demonstrate that our proposed model can synthesize speech with style more appropriate to the input text. First is an emotional corpus on Mandarin, second is a English audiobook dataset. Some samples are provided for comparison. 
**GT** means ground truth. **MRTTS** represents the baseline model we are comparing, and **Proposed** means the proposed TTS with a Contrastive Acoustic-Linguistic Module (CALM), which are described in detail in the paper. 

## emotional corpus on Mandarin
The emotional corpus on Mandarin include six categories (angry, fear, disgust, happy, sad, surprised). Notice that we do not use the emotion labels as supervision in our experiment.

| Text | GT | MRTTS | Proposed |
| :---- | :---- | :---- | :---- | :---- |
| 已经感受到了自己的无比强大了，哈哈！（喜, happy） | <audio controls><source src="./wavs/gt/0.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/baseline/0.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/proposed/0.wav" type="audio/wav">Your browser does not support the audio element.</audio> |
| 他不顾别人怎么议论，竟然扬长而去。（惊, surprised） | <audio controls><source src="./wavs/gt/1.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/baseline/1.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/proposed/1.wav" type="audio/wav">Your browser does not support the audio element.</audio> |
| 天呐，怎么办，她的手里有刀！（恐, fear） | <audio controls><source src="./wavs/gt/2.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/baseline/2.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/proposed/2.wav" type="audio/wav">Your browser does not support the audio element.</audio> |
| 永和豆浆，你不光垃圾还很恶心。（厌, disgust）| <audio controls><source src="./wavs/gt/3.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/baseline/3.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/proposed/3.wav" type="audio/wav">Your browser does not support the audio element.</audio> |
| 我看到正义无法伸张，大家无不感到痛心疾首。(哀, sad) | <audio controls><source src="./wavs/gt/4.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/baseline/4.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/proposed/4.wav" type="audio/wav">Your browser does not support the audio element.</audio> |
| 你不让我好好活着，我也不会让你好过的！（怒, angry） | <audio controls><source src="./wavs/gt/5.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/baseline/5.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/proposed/5.wav" type="audio/wav">Your browser does not support the audio element.</audio> |

## English Audiobook dataset
The second dataset is open-source English audiobook data. The books are read by the 2013 Blizzard Challenge speaker, Catherine Byers.

| Text | GT | MRTTS | Proposed |
| :---- | :---- | :---- | :---- | :---- |
| But when it came to breaking in, that was a bad time for me. | <audio controls><source src="./wavs/gt/6.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/baseline/6.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/proposed/6.wav" type="audio/wav">Your browser does not support the audio element.</audio> |
| Ginger and I had become fast friends, and now I missed her company extremely. | <audio controls><source src="./wavs/gt/7.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/baseline/7.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/proposed/7.wav" type="audio/wav">Your browser does not support the audio element.</audio> |
| I never saw a man so pleased. | <audio controls><source src="./wavs/gt/8.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/baseline/8.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/proposed/8.wav" type="audio/wav">Your browser does not support the audio element.</audio> |
| My friend, Missus Fraser is mad for such a house, and it would not make me miserable . | <audio controls><source src="./wavs/gt/9.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/baseline/9.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/proposed/9.wav" type="audio/wav">Your browser does not support the audio element.</audio> |
| i got up. | <audio controls><source src="./wavs/gt/10.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/baseline/10.wav" type="audio/wav">Your browser does not support the audio element.</audio> | <audio controls><source src="./wavs/proposed/10.wav" type="audio/wav">Your browser does not support the audio element.</audio> |
