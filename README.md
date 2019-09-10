# Vue_homework
AI0101 18號 林忠義

一、參照_LabSteps的步驟，建立所需的資料庫及模組
二、試用並熟悉原本的增查修刪功能，接下來以 Vue.js 實作出相同的功能

步驟
1.在script導入Vue.js：
<script src="https://cdn.jsdelivr.net/npm/vue/dist/vue.js"></script>

2.在<div class="col-sm-4">
  新增 id="lab" 以連結資料庫
  
3.在<script>中，依據新增的id寫下Vue語法
  範例:
  var labApp = new Vue({
      el: "#lab",
      data: {
      newsList: [{
                   //     ymd: "2017-05-01",
                   //     title: "Item 1"
                   // }
                        }]
4.利用下方程式碼到創建好的資料庫中取得資料
  $.get("/home/news", function(e) {labApp.newsList = JSON.parse(e);})
  
5.修改增查修刪功能

  
  
  
  
  
  
  
  
  
