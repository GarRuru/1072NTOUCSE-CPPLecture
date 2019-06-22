## 5-1 List Maker
[ZeroJudge a870](https://zerojudge.tw/ShowProblem?problemid=a870)

**題目說明**  
許多程式設計任務的常見模式，是維護一個經常改變的項目清單，或者需要將輸入/輸出存到一個儲存裝置。而那些記錄的項目可能是一些等待批准的大學申請人。清單要能依照不同的指令，提供不同操作，像插入或刪除。
 
依照下面的功能定義寫一個程式，程式要提供能以下指令：增加、插入和移除。

ADD X：將X加入於清單的最下面。這個指令必須能在空的清單上執行。  
INSERT X N：將X加入N的前面。  
REMOVE X：將X從清單中刪除。  
SHOW：把整份清單列印出來。  
X、N只含大寫英文字元。

**輸入說明**  
輸入包含了一連串的清單指令，其中輸入的項目不會重複出現，輸入SHOW指令表示串流結束。

**輸出說明**  
將清單的操作結果逐個輸出，各個項目之間以一個空白隔開。

**SAMPLE INPUT**  
ADD NEVER  
ADD COLLAR  
INSERT CAT COLLAR  
ADD DOG  
ADD SCARES  
INSERT ANYTHING CAT  
REMOVE CAT  
INSERT THAT SCARES  
REMOVE COLLAR  
INSERT WEAR ANYTHING  
REMOVE DOG  
ADD CAT  
INSERT YOUR CAT  
SHOW  

**SAMPLE OUTPUT**  
NEVER WEAR ANYTHING THAT SCARES YOUR CAT  
