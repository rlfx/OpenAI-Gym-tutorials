# OpenAI Gym Tutorials

這是一個非官方 OpenAI Gym 教學文件，歡迎閱讀 [貢獻者指南](CONTRIBUTE.md) 參與協作

本文件並非單純官方文件翻譯，而是聚焦在：

- 引導簡易實作，從實作中認識 OpenAI Gym 提供的各種函數

    - 在此會假設讀者有基本 Reinforcement Learning 理論知識，不再簡介相關理論公式

    - 如果想要更有系統地學習 Reinforcement Learning，請參考 [awesome-RL](https://github.com/aikorea/awesome-rl) 列表中的相關資源。

- 本文件會特別針對如何 **自訂環境** 做說明，以及適時補充自訂環境會遇到的問題與解決方法
    
    - 在此不會講怎麼使用 render()，而是會多討論怎麼用 Gym Http API 

    - 除非你是要處理遊戲問題，或是要跑別人的環境，否則用 Web 呈現結果會比較容易

## 目錄

 標題　　　　　　　　　　                      | 內容簡介
-----------------------------------------------|--------------------------------------------
1. [套件安裝](chapter-01.md) 　　　　　　　　　| 安裝 Python 與 OpenAI Gym 的教學
2. [建立範例環境](chapter-02.md)               | 透過官方範例認識 gym 以及 env 的基本用法
3. [訓練範例演算法](chapter-03.md)             | 認識 Gym 如何訓練，以及演算法的基本架構
4. [自訂環境（一）環境模組](chapter-04.md)     | 要在 Gym 上面跑，你的環境要提供那些功能
5. [自訂環境（二）回合運算](chapter-05.md)     | 學會寫環境的回合運算函數
6. [自訂環境（三）環境重置](chapter-06.md)     | 學會寫環境的初始與重置函數
7. [自訂環境（四）初始化](chapter-07.md)       | 學會寫環境的初始化函數
8. [Http API（一）啟動伺服器](chapter-08.md)   | 了解 Gym Http API 的伺服器端和客戶端
9. [Http API（二）取得回合結果](chapter-09.md) | 簡易使用 Http API 的教學
10. [安裝與執行常見錯誤](chapter-10.md)        | 列出安裝與執行時的可能錯誤與可能解法
11. [所有函數的使用方法](chapter-11.md)        | 上述未提到的其他 Gym 套件函數的使用說明
12. [中文學習資源列表](chapter-12.md)　　　　　| 中文學習資源列表
　　　　　　　　　　　　　　　|　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　　


　　　　　


