# Web App 社團 AngularJs 分享會

## 範例

一切範例從 angular-seed 出發!

	$ git clone https://github.com/angular/angular-seed

### Controller
	
- ng-app 用來宣告 AngularJs 作用範圍  
ng-app = "module name" 告知 AngularJs 該以哪一個 module 為主

- ng-model 多與 input 交互作用，將 input 結果放到 model 裡，model 值被修改也會直接回來影響 input 的 value

- ng-init 用來初始化一範圍的值，產生獨立的 scope，通常是為了方便不寫 controller 的選項

- ng-click 點擊事件，切記呼叫函式一定要加 ()

- ng-repeat 類似 js 的 foreach

- ng-show ng-hide 控制顯示，隱藏

- ng-class 控制套用的 class

- ng-src 圖片 url 裡有用到 expression 就必須使用 ng-src，因為可能向後台發送 request 時 anguarjs 還沒有 compile 好

- ng-option 類似 ng-repeat，請參考文章 [ngOption 參數用法](http://blog.miniasp.com/post/2013/05/12/AngularJS-ng-module-select-ngOptions-usage-samples.aspx)

### Filter

### Module

- 講解 Dependency Injection

### Router

粉簡單，也因為太陽春了所以常用 UI-router 替代

### directive

### Service 

講解 $http

### Angular UI 介紹

### Require.js

管理相依性跟壓縮代碼

 







 
