container / container-fluid
row
1.display flex
2.flex-wrap 格線可以換列
3.margin-left margin-right負值抵銷左右padding讓.row去抵消，讓格線可以占滿container
    把內部容器分割
        自動分欄col 不會折行
        固定寬col-x
    
        
layout
    [Breakpoints](https://getbootstrap.com/docs/4.5/layout/overview/#containers) 
      >576 手機橫向 
      >768 平板直向包含桌機(ipad ipad pro直向1024 橫向1366)
      >992 平板橫向
      >1400 bootstrap5增加的

    containers

## 01.html
> 5欄頁面
## 02.html
> 手機上是滿版，平板上是3欄
## 03.html
> 自動欄寬，在平板以上才有作用，由row 來設定幾欄
    欄間距可以用g設定
