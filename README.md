# 金魚都能懂得Bootstrap5 網頁框架開發

## [Day02_Bootstrap5安裝與快速檢測方式](https://youtu.be/hKR3Wu6ARSg)
### Bootstrap5 的安裝方式有哪幾種
* npm
* [CDN](https://zh.wikipedia.org/wiki/%E5%85%A7%E5%AE%B9%E5%82%B3%E9%81%9E%E7%B6%B2%E8%B7%AF)
* file
### 怎麼測試Bootstrap5有安裝完成
> 用一個簡單的bootstrap按鈕測試
### 格線系統是採用甚麼CSS屬性製作的
> flex
### 格線系統的container-fluid 是甚麼意思
> container為一個定寬度
### 格線系統的container是作甚麼用的
> 設定頁面寬度為滿版或定寬
### 格線系統預設把畫面分割成幾等分
> 12等分
### 格線系統使用甚麼CSS class名稱來製作多欄畫面
> 手機 sm、平板 md、桌機 lg、大型桌機 xl
### 格線系統的class名稱中，怎樣做到不同裝置不同欄數
> ex. col-12、col-sm-3...
### Note
* [官網](https://v5.getbootstrap.com/)
* [viewport](https://www.w3schools.com/css/css_rwd_viewport.asp)
  > RWD 必設viewport，透過viewport網頁設計是可以控制網頁在不同device能呈現不同的dimension與scaling
* bootstrap5 將jquery拿掉，用原生JavaScript撰寫
* popper.min.js為第三方套件，bootstrap5 download src code中並沒有，直接將cdn網址貼到瀏覽器copy內容

### 實作
* 01
> bootstrap Starter template
* 02
> 使用file引入bootstrap，設計三欄版面，設計不同device有不同的欄


## [Day02_格線系統入門](https://www.youtube.com/watch?v=OfaswRwuWY0&feature=youtu.be)
### 斷點是甚麼
> [Breakpoints](https://v5.getbootstrap.com/docs/5.0/layout/breakpoints/) are the triggers in Bootstrap for how your layout responsive changes across device or viewport sizes.
### 定寬容器是甚麼
> 在不同的device有不同的固定寬度
### 定寬容器的寬度在不同裝置上面會有甚麼變化
> 請參考官網[doc](https://v5.getbootstrap.com/docs/5.0/layout/containers/#how-they-work)
### 格線系統是採用甚麼CSS屬性製作的
> Flex
### row有哪些作用
1. display flex
2. flex-wrap 格線可以換列
3. margin-left margin-right負值抵銷左右padding讓.row去抵消，讓格線可以占滿container
### 怎麼讓格線系統做到滿版
> col-12
### 格線系統預設把畫面分割成幾等分，其原因又是甚麼
> 12等分
### 格線系統使用甚麼CSS class名稱來製作多欄畫面
> col-xx
### 格線系統的兩種控制欄數的作法
1. 自動格線系統，class 設為col會自動分欄，但不會折行
2. 設定格線ex. col-3 col-3 col-3
### Bootstrap5新的格線系統怎麼變更欄與欄之間的間距
> 可利用g-x來設定
### 格線系統的class名稱中，怎樣做到不同裝置不同欄數
> col、col-sm-4等
### Note
* 576 手機橫向 
* 768 平板直向包含桌機(ipad ipad pro直向1024 橫向1366)
* 992 平板橫向
* 1400 bootstrap5增加的
### 實作
* 01
> 5欄頁面
* 02
> 手機上是滿版，平板上是3欄
* 03
>自動欄寬，在平板以上才有作用，由row 來設定幾欄
欄間距可以用g設定

## [Day04_格線的對齊與分佈](https://youtu.be/uJ_LdnvM-D4)
### 對齊的觀念
### justify-content是控制甚麼軸
### justify-content用於「對齊」的class名稱有哪些
### justify-content用於「分佈」的class名稱有哪些
### align-items用於控制哪個軸
### align-items如何用來讓物件置中
### 一開始Amos垂直置中失敗的原因是
### 如何設定區塊的高度為100%