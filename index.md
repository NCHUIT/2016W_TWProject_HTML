title: 台中 Workshop 計畫：HTML 場
author: 中興大學資訊科技研習社

%%%%%%%%%%%%%%%%%%%
% Use '%' to comment or directive (ex:css below)

%%%%%%%%%%%%%%%%%%%
%% You can add some custom style rules here...

%css


.center-list ul, .center-list ol {
    display:table;
    margin:0 auto;
}

%end

%%%%%%%%%%%%%%%%%%%
%% occupation of scale=1:
%% x = 1200
%% y = 700
%% occupation of scale=2: [occupation of scale=1] * 2
%% x = 2400
%% y = 1400
%% occupation of scale=3: [occupation of scale=1] * 3
%% x = 3600
%% y = 2100
%% occupation of scale=4: [occupation of scale=1] * 4
%% ...
%% the location of one step (slide) is originated from the center!

%%%%%%%%%%%%%%%%%%%
%% Here we go...

%%%%%%%%%%%%%%%
!SLIDE x=0 y=0

## 台中 Workshop 計畫：HTML 場

#### 中興大學資訊科技研習社

%%%%%%%%%%%%%%%
!SLIDE picture x=1200 y=0

![finished launch](http://i.giphy.com/26tn5Johfk4VwcF7G.gif)

#### 吃飽囉~

#### 下午我們要來讓 Git 有實際的功用囉！

%%%%%%%%%%%%%%%
!SLIDE x=2400 y=0

## 下午的主題

#### HTML5

#### [http://semantic-ui.com](http://semantic-ui.com)

#### 這邊強者雲集嗎？

%%%%%%%%%%%%%%%
!SLIDE x=3600 y=0

## 請打開各位愛用的編輯器

##### Word 或是記事本(!? 拜偷別)

#### vim  / atom / sublime text

%%%%%%%%%%%%%%%
!SLIDE x=0 y=700

### 第一步：HTML5 基本版型

```
<!DOCTYPE html>
  <html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>Document</title>
  </head>
  <body>
  </body>
</html>
```

%%%%%%%%%%%%%%%
!SLIDE center-list x=1200 y=700

### 放些元素在 `body` 裡頭吧

 * 文字：`h1` - `h6` / `p`
 * 圖片：`<img src="" />`
 * 超連結：`<a href="">...</a>`

%%%%%%%%%%%%%%%
!SLIDE center-list x=2400 y=700

### 再加入些容器吧

 * 表格： `table>tr*3>td*3`
 * 清單： `ol>li*3`
 * 白板：`<div>...</div>`

%%%%%%%%%%%%%%%
!SLIDE center-list x=3600 y=700

### CSS 簡單說明

 * 就是讓你的網頁有 Style
 * 不懂？按下 F12 / CMD+Opt+i 打開開發者介面的第一個工具的右半邊那個就是
 * 對你的文字加個 `color: red;` 試試

%%%%%%%%%%%%%%%
!SLIDE picture x=4800 y=700

### 很醜吧？

![guly html](http://imgur.com/X653dAF.png)

%%%%%%%%%%%%%%%
!SLIDE x=0 y=1400

## Semantic UI

#### 來用別人寫好的 CSS 檔案！

#### 俗話說萬丈高樓平地起，但是我們可以直接搭電梯！

%%%%%%%%%%%%%%%
!SLIDE center-list x=1200 y=1400

### 引入別人寫好的 CSS 檔案！

 * 我們選用 `semantic-ui` ，估狗之
 * `<link rel="stylesheet" href="...">`
 * 估狗 `semantic-ui cdn` ，取得連結

%%%%%%%%%%%%%%%
!SLIDE center-list x=2400 y=1400

### 在 `semantic-ui` 的網站裡遊走

 * 尋找你想要的元件
 * 然後複製 HTML
 * 貼上應該就可以看到東西了

%%%%%%%%%%%%%%%
!SLIDE center-list x=3600 y=1400

### The quickest http server

 1. 下載並安裝 NodeJS
 2. 打開 `CMD` ，輸入 `npm install -g http-server`
 3. 在 windows 上，按著 `shift` 按右鍵選 `在此處開啟命令提示視窗` (或 `cd 你的目錄`) 然後輸入 `http-server`

%%%%%%%%%%%%%%%
!SLIDE center-list x=0 y=2100

### Semantic UI 提供的一些比 HTML 原始好用元件

 * 比 HTML 內建變化多的 [Header](http://semantic-ui.com/elements/header.html)
 * 比 HTML 內建功能豐富的 [Image](http://semantic-ui.com/elements/image.html)
 * 比 HTML 內建超連結美的 [Button](http://semantic-ui.com/elements/button.html)

%%%%%%%%%%%%%%%
!SLIDE center-list x=1200 y=2100

### Semantic UI 提供的一些比 HTML 原始好用容器

 * 比 HTML 內建屌多的 [Table](http://semantic-ui.com/collections/table.html)
 * 比 HTML 內建屌猛的 [List](http://semantic-ui.com/elements/list.html)

%%%%%%%%%%%%%%%
!SLIDE center-list x=2400 y=2100

### Semantic UI 提供的一些原本 HTML 沒有的東西

 * [Icon](http://semantic-ui.com/elements/icon.html)
 * [Segment](http://semantic-ui.com/elements/segment.html)
 * 當然還有很多，要學著自己查資料啊

%%%%%%%%%%%%%%%
!SLIDE center-list x=3600 y=2100

## Semantic UI 的排版用容器

#### 在這之前，有個很重要的概念：

#### [RWD](https://developer.mozilla.org/en-US/docs/Web/Guide/Responsive_design)

%%%%%%%%%%%%%%%
!SLIDE center-list x=3600 y=2100 z=-6000

### Semantic UI 的排版用容器

 * [Grid](http://semantic-ui.com/collections/grid.html)
 * [Container](http://semantic-ui.com/elements/container.html)
 * [關於 viewport 的設定](https://developer.mozilla.org/en-US/docs/Mozilla/Mobile/Viewport_meta_tag)

%%%%%%%%%%%%%%%
!SLIDE x=0 y=2800

## 開始動手！

#### 由助教們提供樣本讓大家開始做囉

#### 有問題都可以問助教

#### [教學資源：http://ppt.cc/rIbyS](http://ppt.cc/rIbyS)

%%%%%%%%%%%%%%%
!SLIDE center-list x=0 y=3500

### 來跟早上的 Git 結合囉，這樣才能把自己的網站弄上去！

 * `git init`
 * `git remote add origin <repo_url>`
 * `git add --all`
 * `git commit -m "..."`
 * `git push`

%%%%%%%%%%%%%%%
!SLIDE x=0 y=4200

## DEMO 時間！

#### 都弄好了嗎？

#### 有沒有自願？

%%%%%%%%%%%%%%%
!SLIDE picture x=0 y=4900

### 謝謝大家今天的參與！

![presents](http://i.imgur.com/3FpJbep.png)

%%%%%%%%%%%%%%%
!SLIDE picture x=0 y=5600

 * 興大資訊社：
   * 粉專：[http://fb.me/it.nchu](http://fb.me/it.nchu)
   * 官方網站：[http://nchuit.cc](http://nchuit.cc)
 * 逢甲黑客社：
   * 粉專：[http://fb.me/HackerSir.tw](http://fb.me/HackerSir.tw)
   * 官方網站：[https://hackersir.info](https://hackersir.info)
 * SITCON:
   * 粉專：[http://fb.me/SITCONtw](http://fb.me/SITCONtw)
   * 官方網站：[http://sitcon.org](http://sitcon.org)

%% The End
%%%%%%%%%%%%%%%
