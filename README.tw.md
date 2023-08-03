<div align="center">
<h1 align="center">
<img width="250" height="100" class="site-logo" src="https://www.iiidevops.org/wp-content/uploads/2021/01/IIIDevOps-logo-01-01.png" alt="III DevOps">
<br>
 III-DevOps-Lite-workshop
</h1>
<h3>◦ 一個整合一系列敏捷開發所需工具與服務 — <a href="https://www.iiidevops.org/">III DevOps Lite</a> 的 Workshop</h3>
<hr/>

<p align="center">

<img src="https://img.shields.io/badge/III DevOps-4fbf8d.svg?style&logoColor=white" alt="III DevOps" />
<img src="https://img.shields.io/badge/php-4d588e.svg?style&logo=php&logoColor=white" alt="php" />
<img src="https://img.shields.io/github/license/ttpss930141011/Gitea-workshop?style&color=5D6D7E" alt="license" />
</p>

<a href="./README.md">English Readme</a> | 繁體中文 Readme

</div>

## **Resources**

### **Introduction**

[開源 III DevOps Lite 版整合工具實作](https://cloudsummit.ithome.com.tw/2023/lab-page/2124)

### **III DevOps**

[III DevOps url](https://www.iiidevops.org/)


## **Foreword**

這個 workshop 是在 Cloud summit 2023 的工作坊，由資策會組長蔡宗榮先生所帶領。

III DevOps 是一個做為 CI/CD 持續整合、持續部署、自動化工具的整合平台，

在這次的 Workshop，將 III DevOps 的大部分功能跑過一遍，將 example repo push 上 III DevOps 上，可以像是 Github 一樣去開 Ticket 並去指定 assigner 與 new branch，在 commit 時經由 SonarQube 去 Detect 程式碼中的問題，協助程式設計者維持程式碼品質、偵測安全性漏洞、減少技術債的累積。他也提供了一個簡單明瞭的 Dashboard，讓 Project owner 與 assigner 都可以在 Dashboard 上追蹤專案進度。

這個專案前端明顯是用 Vue 所撰寫，並套用 vue-admin-template 風格，打開頁面時介面熟悉到會心一笑了一下。


## **Getting started**

### **Installation**



有兩種方法，第一種是如 III DevOps repo 中的 [README](https://github.com/iii-org/deploy-devops-lite/blob/master/README.md) 去安裝部屬，或是使用提供的網址去試用。

>> Note: 在第一種方法中，我沒有看到哪裡可以註冊新用戶的地方，且在 Workshop 中因為大部分的人都沒有現成 VM 可使用，所以大多都是使用第二種方法。

第二種為使用資策會所提供的練功網址，但由於 Cloud summit 已結束，加上文檔中有些關於 IP 的隱私資料，所以就不提供了，僅做為紀錄用。

### Dashboard
在 Dashboard 建立專案之後，相關者皆可以在此頁面追蹤到 Project。
![Dashboard](/images/1691055184369.jpg)
### Project management
可以新增專案成員。
![Project management](/images/1691055209277.jpg)
### Issue
像是 Github 的 Project 功能，可以新增 Ticket 並 assign 人，比較酷的是在 Ticket 中有其他自定義選項，例如說完成度...等。
![Issue](/images/messageImage_1691055301036.jpg)
### Project dashboard
在 Project dashboard 中可以看到每個 Project 的狀態。
![Project dashboard](/images/1691056523110.jpg)
### Pipeline
在此頁面可以看到每次 commit 之後跑的 pipeline 結果。
![pipeline](/images/1691054854082.jpg)
### SonarCube
只要是 III DevOps 支援的語言就可以套用 SonarCube 白箱測試，目前支援 php、Python flask、.NET Core、Java 8。
![SonarCube](/images/1691055429962.jpg)

## Epilogue

總的來說，III DevOps 是一個全面的 DevOps 整合產品，但我私心來說還是會比較喜歡用 Github，畢竟有 Code review 功能，repo 中 branch 的權限也可以自定義，但我想這應該也會在 III DevOps 的 feature todolist 上，期待此產品之後的發展。 