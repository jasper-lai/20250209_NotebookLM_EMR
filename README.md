# 初探 NotebookLM：以 醫療機構電子病歷製作及管理辦法 為例

## 前言

最近整個 AI 軟體業有了長足的發展, 各平台及工具百家爭鳴, Will 保哥在去年底整理了 <a href="https://www.facebook.com/groups/gaitech/permalink/1295834858267393" target="_blank">日常 AI 工具: 2024 Q4 版本</a>, 說明各工具的適用情境.  

本文主要利用 <a href="https://notebooklm.google.com/" target="_blank">Google NotebookLM</a> 工具, 將 <a href="https://law.moj.gov.tw/LawClass/LawAll.aspx?pcode=L0020121" target="_blank">醫療機構電子病歷製作及管理辦法</a> 的內容進行整理, 並產生複習用的題庫.  

NotebookLM 可以適用在以下的情境:
1. 經由其整理的總結, 快速大略得知資料來源的摘要.  
2. 幫忙整理內容, 產生題庫, 供複習之用.  

**提醒一下, 雖然可以幫忙作內容整理, 但書還是要自己讀, 不能只看 AI 整理出來的總結, 很容易會失去洞見 (InSight)**

以下是 "Will 保哥的技術交流中心" 的貼文. (2025.01.11)  
> AI 不能取代你本來就該讀書這件事，不要太相信總結這種東西，知道個大概不能讓你對知識產生洞見，沒有洞見就無法替你帶來價值！ (by Will保哥)

## 什麼是 NotebookLM 筆記工具:

1. NotebookLM 是由Google開發的AI筆記工具
2. NotebookLM最核心的應用情境就是協助使用者整理和分析各種資料, 支援的來源種類如下:
    - 上傳檔案: PDF, TXT, Markdown, 音訊 (例如: MP3)
    - Google 雲端硬碟
	    - Google 文件
	    - Google 簡報
    - 連結
	    - 網站 
		    - 例如: <a href="https://law.moj.gov.tw/LawClass/LawAll.aspx?pcode=L0020121" target="_blank">(全國法規資料庫) 醫療機構電子病歷製作及管理辦法</a>  
		- Youtube
    - 貼上文字
	    - 複製的文字
3. NotebookLM會自動分析其内容, 並生成「筆記本導覽」其中包含
    - 摘要  
    - 音訊總覽(2024) or 深入探索對話(2025)  
    - 學習指南  
    - 簡介文件(2024) or 簡報文件(2025)  
    - 時間軸  
    - 常見問題  
    - 目錄(2024 only)  

## NotebookLM 架構圖

黃底的部份為 NotebookLM 的範圍.  
因為還沒有試過虛線的部份, 故不列入本文的範圍.  

![01 NotebookLM_架構圖](pictures/01-NotebookLM_架構圖.png)  


## NotebookLM 隱私權聲明

- 資料來源: <a href="https://notebooklm.google/" target="_blank">notebooklm.google</a>   

![02 NotebookLM_隱私權聲明](pictures/02-NotebookLM_隱私權聲明.png)  


## 以 醫療機構電子病歷製作及管理辦法 為例

### STEP 1: 建立來源

- 進入首頁: <a href="https://notebooklm.google.com/" target="_blank">notebooklm.google.com</a>  

- 新增 **筆記本**  

![11 NotebookLM_新增筆記本](pictures/11-NotebookLM_新增筆記本.png)  

- 修改 **筆記本** 名稱, 並 **新增來源**  

![12 NotebookLM_新增來源](pictures/12-NotebookLM_新增來源.png)  

可以由下圖看出支援的來源有那些, 因為 **醫療機構電子病歷製作及管理辦法** 是屬於 **連結**, 所以選取 **網站** 後, 輸入連結.  
![13 NotebookLM_新增來源_連結](pictures/13-NotebookLM_新增來源_連結.png)  
![14 NotebookLM_新增來源_EMR製作管理辦法](pictures/14-NotebookLM_新增來源_EMR製作管理辦法.png)  

結果發現來源有限制, 無法匯入該網頁. (註: 2024.12 是可以匯入的狀態, 不知這段期間發生了什麼事...)  
![15 NotebookLM_新增來源_EMR製作管理辦法_無法匯入連結](pictures/15-NotebookLM_新增來源_EMR製作管理辦法_無法匯入連結.png)  

山不轉路轉, 那就把法律條文下載之後, 再上傳到 NotebookLM 作處理.  
![21 下載_EMR_法律條文](pictures/21-下載_EMR_法律條文.png)  
![22 下載_EMR_法律條文_PDF](pictures/22-下載_EMR_法律條文_PDF.png)
![23 上傳_EMR_法律條文_PDF](pictures/23-上傳_EMR_法律條文_PDF.png)  
![24 上傳_EMR_法律條文_PDF](pictures/24-上傳_EMR_法律條文_PDF.png)  
![25 上傳_EMR_法律條文_成功](pictures/25-上傳_EMR_法律條文_成功.png)  

上傳完成了, 點取上張圖的黃框部份, 可以看一下 NotebookLM 的初步整理.  
![26 EMR_法律條文_初步分析結果](pictures/26-EMR_法律條文_初步分析結果.png)  

### STEP 2: 利用 NotebookLM 自動整理記事

1.. 自動整理記事的功能, 在右方的 Studio 區塊.  
![31 NotebookLM_自動生成記事](pictures/31-NotebookLM_自動生成記事.png)  

2.. 上圖有 5 項功能.  

**(1) 深入探索對話.**  
- 產生 2位 主持人 的語音對話. 但有個限制, 即使來源是中文, 它還是只產生英文的對話. 或許可以期待一下, 後續可以作出中文對話的功能.  
- **好消息** 2025.05 起, 已支援產生中文語音對話.  

![32 NotebookLM_自動生成記事_語音對話_1](pictures/32-NotebookLM_自動生成記事_語音對話_1.png)  
![32 NotebookLM_自動生成記事_語音對話_2](pictures/32-NotebookLM_自動生成記事_語音對話_2.png)  

**(2) 研讀指南.**  
- 產生重點提示問答題, 代表 NotebookLM 認為的重點.  

![34 NotebookLM_自動生成記事_研讀指南_1](pictures/34-NotebookLM_自動生成記事_研讀指南_1.png)  
![34 NotebookLM_自動生成記事_研讀指南_2](pictures/34-NotebookLM_自動生成記事_研讀指南_2.png)  

**(3) 簡報文件.**  
- 這個看起來也是很像摘要, 而不是產生 PowerPoint 檔喔.  

![36 NotebookLM_自動生成記事_簡報文件_1](pictures/36-NotebookLM_自動生成記事_簡報文件_1.png)  
![36 NotebookLM_自動生成記事_簡報文件_2](pictures/36-NotebookLM_自動生成記事_簡報文件_2.png)  

**(4) 時間軸.**  
- 從一堆文件中, 取出與時間相關的資料, 通常用在 歷史 / 國文 會很有用.  

![38 NotebookLM_自動生成記事_時間軸_1](pictures/38-NotebookLM_自動生成記事_時間軸_1.png)  
![38 NotebookLM_自動生成記事_時間軸_2](pictures/38-NotebookLM_自動生成記事_時間軸_2.png)  

**(5) 常見問題.**  
- 有點類似 **問題指南**, 也是以問答的方式呈現.  

![40 NotebookLM_自動生成記事_常見問題_1](pictures/40-NotebookLM_自動生成記事_常見問題_1.png)  
![40 NotebookLM_自動生成記事_常見問題_2](pictures/40-NotebookLM_自動生成記事_常見問題_2.png)  

### STEP 3: 利用 NotebookLM 產生題庫

1.. 提示語 (Prompt)

```plaintext

請幫我設計一份10題的考卷, 全部都用選擇題, 單選, 考試內容清從來源出題, 請在最後面統整每題的答案與解說。
每題的文字排版結構如下, 請避免使用任何 Markdown 格式, 不要加上 Inline code fence, 該斷行的要斷行, 每題之間要間隔兩個空白行:

1. 題目
  A.選項A
  B.選項B
  C.選項C
  D.選項D
  
```

2.. 處理的結果  
畫面看來沒有答案選項沒有斷行, 但實際複製後, 會有斷行的效果.  

![51 NotebookLM_EMR_題庫](pictures/51-NotebookLM_EMR_題庫.png)  

```plaintext
好的，這是一份根據您提供的法規內容設計的10題單選選擇題考卷，包含答案與解說：

1. 依據醫療機構電子病歷製作及管理辦法，**醫療機構若要實施電子病歷，應具備的管理機制**不包含下列哪一項？
  A.標準作業機制
  B.權限管控機制
  C.成本效益評估機制
  D.系統安全機制

2. 依據醫療機構電子病歷製作及管理辦法，**下列哪一項不屬於系統安全機制**中應包括的其他保護措施？
  A.使用者身分之確認
  B.個人資料顯示之隱碼或其他適當保護措施
  C.系統開發、上線、維護及應用軟體之驗證確認程序
  D.定期更換醫療機構負責人

3. 依據醫療機構電子病歷製作及管理辦法，醫療機構發生安全事故時，若影響營運或當事人權益，應於知悉事故發生起多久時間內通報主管機關？
  A.24小時
  B.48小時
  C.72小時
  D.1週

4. 依據醫療機構電子病歷製作及管理辦法，**醫療機構委託受託機構建置及管理系統**，下列敘述何者錯誤？
  A.應訂定書面契約
  B.委託所屬醫療法人之其他附設醫院，得免訂定書面契約
  C.受託機構應通過中央主管機關認可之資訊安全標準驗證，並有證明文件
  D.受託機構可再委託第三人為之

5. 依據醫療機構電子病歷製作及管理辦法，**關於雲端服務**，下列敘述何者錯誤？
  A.應採取適當風險管控措施
  B.資料儲存地點應設置於我國境內
  C.可不採取避免醫療業務中斷措施
  D.應對雲端服務業者進行監督

6. 依據醫療機構電子病歷製作及管理辦法，醫療機構實施電子病歷者，應於開始實施之日起多久時間內報主管機關備查？
  A.7日內
  B.10日內
  C.15日內
  D.1個月內

7. 依據醫療機構電子病歷製作及管理辦法，**病歷製作後**，應於多久時間內完成電子簽章？
  A.6小時
  B.12小時
  C.24小時
  D.48小時

8. 依據醫療機構電子病歷製作及管理辦法，**電子病歷的存取、增刪等相關事項**，應保存完整紀錄多久？
  A.3年
  B.5年
  C.7年
  D.10年 (應保存至本法第七十條第一項所定病歷保存期間)

9. 依據醫療機構電子病歷製作及管理辦法，**下列何者可以轉錄為電子檔案保存**，並視同電子病歷？
  A.應以書面同意且併同病歷保存之文件
  B.醫療機構電子病歷實施前既有之紙本病歷
  C.其他依法令規定應併同病歷保存之文件、資料
  D.以上皆是

10. 依據醫療機構電子病歷製作及管理辦法，**醫療機構進行電子病歷交換或利用**，應經誰同意？
  A.病人
  B.直轄市、縣（市）主管機關
  C.中央主管機關
  D.醫療機構負責人
```

**答案與解說：**  

```plaintext
1.  C
    *   解說：依據第三條第一項，醫療機構實施電子病歷應具備的管理機制包含標準作業、權限管控、緊急應變、系統安全、傳輸加密及安全事故處理機制，**不包含成本效益評估**。

2.  D
    *   解說：依據第四條，系統安全機制應包括使用者身分確認、個人資料保護、系統驗證程序、系統使用及資料存取監控、網路入侵防範及非法或異常使用之因應措施，**不包含定期更換醫療機構負責人**。

3.  C
    *   解說：依據第五條第二項，**應於知悉事故發生起72小時內通報**直轄市、縣（市）主管機關。

4.  D
    *   解說：依據第七條第十項，**受託機構不得再委託第三人為之**，除非經醫療機構同意，並於契約載明再委託事項等。

5.  C
    *   解說：依據第八條第一項第二款，應採取**避免醫療業務中斷措施**。

6.  C
    *   解說：依據第九條，應於**實施之日起十五日內**報直轄市、縣（市）主管機關備查。

7.  C
    *   解說：依據第十一條第一項第四款，病歷製作後，應於**二十四小時內**完成電子簽章。

8.  D
    * 解說： 依據第十三條，電子病歷之存取、增刪、查閱、複製與其他相關事項，及其執行人員、時間與內容，應保存完整紀錄至**本法第七十條第一項所定病歷保存期間**。

9.  D
    *   解說：依據第十七條第一項，**以上皆是**可以轉錄為電子檔案保存，並視同電子病歷。

10. A
    *   解說：依據第十九條第一項，醫療機構依前條第一項交換平臺為電子病歷交換或利用時，**應經病人同意**。
```


## 參考文件

* <a href="https://www.facebook.com/groups/gaitech/permalink/1295834858267393" target="_blank">(Will保哥) 日常 AI 工具: 2024 Q4 版本</a>  

* <a href="https://law.moj.gov.tw/LawClass/LawAll.aspx?pcode=L0020121" target="_blank">(全國法規資料庫) 醫療機構電子病歷製作及管理辦法</a>  

* <a href="https://www.facebook.com/will.fans/posts/pfbid02QFvbMTTm3ck8nbYy479EzvwXx3oJ7JohyBmyG9doyza2qKPNwE5D2rAn1yGsLrBxl" target="_blank">(Will保哥) NotebookLM 總結, 洞見與價值</a>  

* <a href="https://www.bnext.com.tw/article/81728/notebooklm-tutorial" target="_blank">(數位時代) NotebookLM教學｜NotebookLM是什麼？如何快速消化大量文本、生成摘要？</a>  

* <a href="https://www.youtube.com/watch?v=C6XS8WM_Ias" target="_blank">(雲云工作室) (Youtube)  NotebookLM 語音轉文字逐字稿</a>  
> 2025.05 起, 已支援產生 中文語音 對話


