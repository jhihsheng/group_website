---
title: 📊 光子與電漿晶體的計算與模擬
linkTitle: 光子與電漿晶體
summary: 學習與計算光子能帶，並運用於設計拓樸光子波導
authors: ["admin"]
date: '2022-03-25'
weight: 10
type: book
---

{{< toc hide_on="xl" >}}

在光學的研究與應用裡，如何控制光的流動是一個很基本的問題，常見的工具如
透鏡、反射鏡、波導、偏振片、分光鏡、共振腔、光纖等。
自從 1987 年後，科學家們從固態材料裡的電子能帶 (band structure)
得到啟發，提出了光子晶體的概念，創造出光子能帶 (photonic band structure)，
實現了光子的慮波元件。
### 光子晶體
光子晶體其實就是有週期結構的介電材料，
也就是介電函數 $\epsilon$ 是一個位置的週期函數。
![png](/uploads/pc_1.png)
根據 [Bloch's theorem](https://en.wikipedia.org/wiki/Bloch%27s_theorem) 只要是週期的結構，就會造成能帶結構，底下是一個二維光子晶體的例子，
![png](/uploads/pc_2.png)
光子能隙也被用來製造各種光學元件，在90年代後有了更多實驗與商業上的使用。
![png](/uploads/pc_3.png)
### 電漿晶體
在2000年以後，大家開始研究縮小光學元件的可能性，其中一個方式就是使用奈米金屬結構來達到次波長的結構，
到了2010年以後，週期性的奈米金屬結構得到了更多關注，
![png](/uploads/pc_4.png)
藉由金屬所提供的表面電漿共振 (surface plasmon resonance)， 光學元件得以縮小到奈米尺度。

在這個題目裡，你將學習到電磁學進階的理論與計算技巧，以這些知識來設計
有趣與創新的光子晶體，而其中一個我們有興趣的題目是拓樸光子晶體。

- 奈米光學理論
- 以 python 做數值計算 
- 時域有限差分法 (FDTD) 來解電磁學問題 [MEEP](https://meep.readthedocs.io/en/latest/)
- Analytical methods in EM





參考資料：
1. [Photonic Crystals: Molding the Flow of Light ](http://ab-initio.mit.edu/book/photonic-crystals-book.pdf).
2. [Plasmonic Surface Lattice Resonances: Theory and Computation](https://pubs.acs.org/doi/10.1021/acs.accounts.9b00312).



