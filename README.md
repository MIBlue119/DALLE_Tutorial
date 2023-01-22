# DALLE_TUTORIAL

## 簡介

- DALLE-2 為Open AI的AI文字生成圖像模型，可依據所輸入的文字描述(景像/風格/繪畫方式)而生成圖像。
- 服務網址: https://openai.com/dall-e-2/

## 使用方式

- 依據需求輸入prompt(提示)文字生成
- 可針對生成圖片再做變化
- 可上傳圖片，從圖片生成變化的圖片

### 資源

- open ai dalle2的 ig: https://www.instagram.com/openaidalle/
- 透過圖片來生成prompt

  - CLIP-Interrogator（ [https://bityl.co/Gmu4](https://bityl.co/Gmu4?fbclid=IwAR3liW2PgeWJ92_tJ9jLjSVbpB5SU1ava-kTMP9K8kuLm1fZIWP27w-fRFA) ）這個「以圖算文」的網站，把剛剛你下載下來喜歡的圖片丟上去。該網站會產生一段描述你的圖之「提詞（Prompts）」。可以修改提詞後使用之。
  - 在圖片下方的「clip_model_name（模型名稱）」，選擇比較新的 ViT-H-14/laion2b_s32b_79k 這個 Stable Diffusion 2 演算法模型
- Let the chatGPT to be a prompt generator

```
You are now a DALLE-2 prompt generation tool that will generate a suitable prompt for me to generate a picture story based on the story I give, generate a prompt that gives the DALLE-2 AI text to generate a picture model, please narrate in English and need to maintain a hand drawn style. The prompt I give will be given to you with “” around the text.
```


## 提示關鍵詞

### 鏡頭

- macro 35mm photograph : 微距鏡頭方式生成

### 以畫家名稱

- art by Monet
- in the style of Andy Warhol

### 以畫來描述

- In a style of starry night 

### 以時代/ 場景來描述

- as a 1990s Saturday morning cartoon
- drawn on a cave wall : 畫在洞窟牆壁上
- spray-painted on a wall : 畫在路邊牆壁上
- on the moon in the 1980s : 1980登月場景
- underwater with 1990s technology

### 風格

- Pencil and water color drawing 
- Oil painting 
- Pixel art // 點陣風格
- One line drawing // 單線風格
- Crayon drawing //蠟筆
- Digital art
- ink painting
- Pencil and water color painting
- Expressive oil painting
- Japan ukio-e : 浮世繪
- Photorealistic style ：照相寫實主義
- vaporwave style : 電子音樂和視覺藝術類型
- Pencil drawing
- Steampunk style : 蒸汽時代風格
- in a minimalist style : 極簡主義

### 材質

- Stained glass window 
- made out of plasticine
