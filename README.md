<div align="center">
<h1 align="center">
<img width="250" height="100" class="site-logo" src="https://www.iiidevops.org/wp-content/uploads/2021/01/IIIDevOps-logo-01-01.png" alt="III DevOps">
<br>
III-DevOps-Lite-workshop
</h1>
<h3 align="center">◦ A workshop integrating a series of tools and services required for agile development — <a href="https://www.iiidevops.org/">III DevOps Lite</a>.</h3>
<hr/>
<p align="center">
<img src="https://img.shields.io/badge/III DevOps-4fbf8d.svg?style&logoColor=white" alt="III DevOps" />
<img src="https://img.shields.io/badge/php-4d588e.svg?style&logo=php&logoColor=white" alt="php" />
<img src="https://img.shields.io/github/license/ttpss930141011/Gitea-workshop?style&color=5D6D7E" alt="license" />
</p>
English Readme | <a href="./README.tw.md">繁體中文 Readme</a>

</div>


## **Resources**

### **Introduction**

[Introduction to Open-source III DevOps Lite Integration Tools](https://cloudsummit.ithome.com.tw/2023/lab-page/2124)

### **III DevOps**
[III DevOps url](https://www.iiidevops.org/)

## **Foreword**
This workshop took place at Cloud Summit 2023 and was led by Mr. Tsa Tzung-Jung, the team leader of III.

III DevOps is an integrated platform for Continuous Integration (CI), Continuous Deployment (CD), and automation tools.

During this workshop, participants went through most of the features of III DevOps Lite, pushing example repositories to III DevOps. Similar to Github, participants could open tickets and assign assignees and new branches. SonarQube was used to detect code issues during commits, helping programmers maintain code quality, detect security vulnerabilities, and reduce technical debt accumulation. The platform also provided a straightforward dashboard for Project Owners and assignees to track project progress.

The front-end of this project is clearly written in Vue.js and adopts the vue-admin-template style, making the interface familiar and easy to navigate.

## **Getting started**

### **Installation**
There are two methods to install III DevOps Lite. The first method can be found in the III DevOps repo's README, or you can use the provided website to try it out.

>> Note: In the first method, I did not see any registration process for new users. As most participants in the workshop did not have readily available VMs, the second method was widely used.

The second method involves using the practice website provided by III. However, since Cloud Summit has ended and there are some privacy-related IP details in the documentation, it will not be provided here and is solely for record purposes.

### **Dashboard**
After creating a project in the Dashboard, relevant parties can track project progress on this page.
![Dashboard](/images/1691055184369.jpg)

### **Project management**
Project members can be added.
![Project management](/images/1691055209277.jpg)
### **Issue**
Similar to Github's Project feature, tickets can be created and assigned to individuals. Cool custom options are available in tickets, such as completion status, and more.
![Issue](/images/messageImage_1691055301036.jpg)
### **Project dashboard**
Project statuses can be seen in the Project dashboard.
![Project dashboard](/images/1691056523110.jpg)
### **Pipeline**
This page shows the results of pipelines running after each commit.
![pipeline](/images/1691054854082.jpg)

### **SonarCube**
SonarCube is available for white-box testing for any language supported by III DevOps, including php, Python flask, .NET Core, and Java 8.
![SonarCube](/images/1691055429962.jpg)

## **Epilogue**
Overall, III DevOps is a comprehensive DevOps integration product. However, personally, I still prefer using Github because of its code review feature and customizable branch permissions. Nevertheless, I believe these features will be on the III DevOps feature to-do list, and I look forward to its future development.





