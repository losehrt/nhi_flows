# 一起來畫圖 :paintbrush:
**協同作業**是開放原始碼(Opensource)專案中常見的運作方式，在[衛福部資訊處 *龐一鳴處長* 高呼-醫療上雲](https://www.cio.com.tw/pang-yuming-data-security-cloud-up-medical-ai-as-governors-second-pulse/?utm_source=line&utm_medium=live&utm_campaign=220523)及受疫情干擾之際，「*遠距工作、橫向溝通、斜槓技能*」就顯得份外重要，歡迎大家一起來畫圖，邁向雲端之路。
## 你需要準備的工具及具備的知識

**本專案使用 markdown[^1] 撰寫說明文件及 drawio 繪製 SVG[^2] 格式圖片**

### 1. 註冊 github 帳號
- 若您想要嘗試協同畫圖，開始之前請先到[這裡](https://github.com/signup?ref_cta=Sign+up&ref_loc=header+logged+out&ref_page=%2F&source=header-home)註冊一個 github 帳號

![註冊步驟](./images/github/registration.drawio.svg)
### 2. 安裝 vscode
功能強大且免費使用的文字編輯器，是許多開發者的最愛。
- 一般使用者也可以用它來解決文字編輯的疑難雜症。
- 從[這裏下載](https://code.visualstudio.com/)安裝。
**vscode 參考畫面**
![](./images/vscode/sample.drawio.svg)


### 3. 安裝 drawio 套件
drawio 是一套功能強大且免費使用的線上繪圖軟體，可以快速繪製出流程圖(flowchart)或資訊圖表(Infographic)，內建有多種元素及各式樣板，並提供 png, svg 等多種圖片格式匯出功能，習得此軟體保證值回票價，您可以先[前往該網站](https://app.diagrams.net/)試試。
- 直接在 vscode 安裝外掛模組畫圖[^1]，本專案使用此方法並儲存為向量圖格式SVG[^2]。

- 網路有一些 vscode + drawio 教學，建議您先去看看再回來喔！
  1. [vscocde 安裝網路教學](https://ithelp.ithome.com.tw/articles/10236346)
  2. [影片教學](https://youtu.be/AdrFG7sq1d4)

**drawio 參考畫面**
![](.)

### 4. 安裝 git 軟體
git 是文字檔案內容版本控制的軟體，經常被使用在程式開發的原始碼管理，由於它只針對文字內容做比對，因此，本專案的繪圖協作就採用可縮放向量圖片格式(SVG)來實作圖片版次的管控。
- 版本控制
- 合併請求
協作時，為了做檔案的版本控制，開始之前，我們也須先安裝 git 軟體，以利我們將專案複製(clone)到本地端的電腦，進行畫圖或編寫文字內容。
- 安裝 git 版本控制軟體 [請到這裡下載](https://git-scm.com/download)，並依照您電腦的作業系統，下載相對版本的 git 軟體安裝。
![](./images/git/install.drawio.svg)

- 若您有安裝上的問題，可以看看 [windows 上的 git 安裝教學](https://w3c.hexschool.com/git/3f9497cd)參考，或是留言發問。

- 最後，我們可以檢查看看，您電腦的 git 是否安裝成功？請開啟終端機，並執行執行下列指令：
```
# 檢查 git 版本
git --version
```
```
# 結果輸出
git version 2.24.3 (Apple Git-128)
```


### 5. markdown
- 輕量版的文字排版格式[^4]
## 開始協作
### 1. 複製分支成為自己的專案

- [複製專案的快速連結](https://github.com/losehrt/nhi_flows/fork)(須先登入 github)

- 或是您也可以登入 github 網站後，再複製專案，步驟如下圖所示：
  1. 搜尋「nhi_flows」專案
  2. 點取該專案後，點取右上角「fork」，按建立即可
![](./images/fork.drawio.svg)


![](./images/vscode.drawio.svg)

### 5. 將專案載入 vscode
當所有準備工作都已經完成之後，我們可以開啟 vscode(假設您已經根據上一小節所述，已安裝 vscode 及 drawio 套件)，如下圖所示：

![](./images/startup.drawio.svg)
你可以直接
- 從 Github 複製
- 自己複製網址，如： https://github.com/NickleCheng/nhi_flows.git

[^1]: [vscode drawio 套件](https://github.com/hediet/vscode-drawio)
[^2]: [可縮放向量圖形](https://zh.m.wikipedia.org/zh-tw/%E5%8F%AF%E7%B8%AE%E6%94%BE%E5%90%91%E9%87%8F%E5%9C%96%E5%BD%A2)
[^4]: [markdown 編寫及語法](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)