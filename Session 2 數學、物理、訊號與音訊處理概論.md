# [Session 2] 2024-03-01(四) 數學、物理、訊號與音訊處理概論 
112學年度 下學期 生成式演算互動藝術實作 - 吳哲宇

跟同學們說聲不好意思，上週因病講義提供的較晚，下堂課會視講解情況決定是否找時間補課

以下提供此週內容講義，目標為切入我們能夠在生成式藝術領域使用到的知識，並讓大家有跨領域的連結認識，對於很多數學、物理與系統相關的知識，其實會有很多同源的概念。

請大家根據講義與作業先閱讀範例與資料，有興趣鑽深的同學，可以提前閱讀補充教材中幾個非常經典的資源（裡面有很多在網頁上面可以玩的Demo，我亦會在課堂中帶著大家看)。

## 學習目標
* 數學函數形狀與模式
* 了解物理模擬跟演算法在藝術作品的應用 
* 分析使用在創作的範例
* 了解音樂從數學訊號產生的作法


## 從生成式藝術切入
從亂數、向量、震盪、粒子系統到碎形，我們在基礎與物理的世界中可以找到很多創作的工具，當規則與系統定義得當時，可以「湧現」複雜的行為

### The Nature of Code - DANIEL SHIFFMAN (https://www.youtube.com/watch?v=6vX8wT1G798)
0. Randomness
1. Vectors
2. Forces
3. Oscillation
4. Particle Systems
5. Autonomous Agents
6. Physics Libraries
7. Cellular Automata
8. Fractals
9. Evolutionary Computing
10. Neural Networks
11. Neuroevolution


## 數學
* 三角函數 - sin / cos / tan
    * 靈魂魚
        * https://creativecoding.in/2023/03/02/soul-fish-process/
* 向量 - Vector Math
    * 3Blue1Brown 向量的概念 https://www.youtube.com/watch?v=fNk_zzaMoSs
    * 向量場案例 
        * Dipolar https://www.artblocks.io/collections/curated/projects/0x99a9b7c1116f9ceeb1652de04d5969cce509b069/385
* 機率分布
    * 使用在筆刷與作品
    * Takawo 老師的筆刷範例
        * https://note.com/outburst/n/n631a3845186c
    * 筆刷製作範例
        * https://openprocessing.org/sketch/1782327
* 其他常用工具
    * 餘數 / Lerp / acos 角度轉換

## 演算法類型
* 自然噪聲 (Perlin Noise) 2d / 3d / 4d
    * https://rtouti.github.io/graphics/perlin-noise-algorithm
    * 經典案例 Meridian
        * https://www.artblocks.io/collections/presents/projects/0xa7d8d9ef8d8ce8992df33d8b8cf4aebabd5bd270/163
    * 經典案例 Subscapes
        * https://www.artblocks.io/collections/curated/projects/0xa7d8d9ef8d8ce8992df33d8b8cf4aebabd5bd270/53
* Circle Packing
    * https://en.wikipedia.org/wiki/Circle_packing
    * 經典案例 QQL
        * https://qql.art/
    * 作品範例
        * https://openprocessing.org/sketch/887516
* 遞迴切割 / Fractal
    * https://en.wikipedia.org/wiki/Fractal_art
    * 遞迴切割案例
    * Edifice https://www.artblocks.io/collections/curated/projects/0xa7d8d9ef8d8ce8992df33d8b8cf4aebabd5bd270/204
* L-systems
    * https://en.wikipedia.org/wiki/L-system
    * 作品範例：
        * https://openprocessing.org/sketch/612674
* Voronoi Diagrams
    * 作品範例
        * https://openprocessing.org/sketch/855229
* Cellular Automata 細胞自動機
    * 生命遊戲 Game of Life
        * https://zh.wikipedia.org/zh-tw/%E5%BA%B7%E5%A8%81%E7%94%9F%E5%91%BD%E6%B8%B8%E6%88%8F


## 物理
* 粒子模擬 
    * https://en.wikipedia.org/wiki/Particle_system
    * https://experiments.withgoogle.com/experiments?tag=Particles
* 光與疊色
    * 光的三原色與疊色模式
    * https://zh.wikipedia.org/zh-tw/%E4%B8%89%E5%8E%9F%E8%89%B2%E5%85%89%E6%A8%A1%E5%BC%8F
    * 印刷與螢幕顯示的色域
* GLSL
    * Shader
        * https://www.shadertoy.com/
* 一些函式庫：
    * Matter.js

## 系統與數據
* 有限狀態自動機(FSM) - 常用來管理藝術作品的狀態轉變 / 生成式音樂
    * https://zh.wikipedia.org/zh-tw/%E6%9C%89%E9%99%90%E7%8A%B6%E6%80%81%E6%9C%BA
* Feedback Loop
* 數據轉換成藝術 Dear Data
    * https://www.dear-data.com/theproject


## 音訊
* 音訊合成原理 - 圓波方波三角波
    * 合成器
* 噪聲 (White Noise / Pink Noise)
    * 聲音示意 https://www.youtube.com/watch?v=aiyh2j-BfkQ
* ADSR https://filmmusic101.com/blog/envelope%E6%B3%A2%E5%B0%81%E7%B0%A1%E4%BB%8B/
* 軟體：MaxMSP / Ableton Live
* Chrome Music Lab https://musiclab.chromeexperiments.com/
* Tone.js 
    * https://tonejs.github.io/examples/
* Audio Visual 必備工具 - 傅立葉分析與圖面頻率
    * 頻率 -> 訊號組成 
    * https://www.youtube.com/watch?v=spUNpyF58BY&pp=ygUSZm91dXJpZXIgdHJhbnNmb3Jt


## 參考資料
Nature of Code https://natureofcode.com/
Learning Synth https://learningsynths.ableton.com/en/
Learning Music https://learningmusic.ableton.com/
The Book of Shaders https://thebookofshaders.com/
The Coding Train - Nature of Code https://www.youtube.com/watch?v=6vX8wT1G798


## 作業
[Week2 作業](https://docs.google.com/document/d/11ftFL4PhEMP20JcaAvzi5GX3YwUzQsFqtYe1Gyi9wl4/edit)