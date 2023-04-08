1. 建議在第六點之前，完成[Laravel Learning Path](https://github.com/JYu1999/BackendLearningPath/blob/master/Laravel%20Learning%20Path.md)
2. 先了解 hosting 是什麼，有哪些種類
   - [不是工程師 架站用VPS還是Web Hosting，中文翻譯都有「虛擬」到底差在哪？](https://progressbar.tw/posts/102)
   - [學習VPS的重要性與各大Linux VPS 比較與推薦 (Linode, DigitalOcean, Vultr, AWS Lightsail)
](https://progressbar.tw/posts/131)
3. 想辦法開一個 VPS 或 Cloud Host，然後 ssh 進去
    在下面的步驟中，我使用的作業系統主要是 ubuntu，如果你心有餘力的話，最好是也把紅帽系列(CentOS, Rocky)的也部署看看。
4. 安裝 LEMP
   - [How To Install Linux, Nginx, MySQL, PHP (LEMP stack) on Ubuntu 22.04](https://www.digitalocean.com/community/tutorials/how-to-install-linux-nginx-mysql-php-lemp-stack-on-ubuntu-22-04)
   - [How To Install LEMP Stack On Ubuntu 22.04](https://cloudcone.com/docs/article/how-to-install-lemp-stack-on-ubuntu-22-04/)
   - 安裝過程中，務必注意啟用 ufw 之後，要把 ssh 開起來，否則會出現 server 還活著，但就是 ssh 不進去的狀況。
     - [Ufw Firewall Allow SSH](https://linuxhint.com/ufw-firewall-allow-ssh/)
     - [How To Install MariaDB on Ubuntu 22.04](https://www.digitalocean.com/community/tutorials/how-to-install-mariadb-on-ubuntu-22-04)
5. (optional) 在這邊最好把使用的 web server 摸透，反正遲早的事情。有了前面 Linux 的經驗，這個應該不算太難（吧）XD 
   [【尚硅谷】2022版Nginx教程（进阶高程架构师必备）](https://youtube.com/playlist?list=PLmOn9nNkQxJFKkgL4kqBtbX3J2FHmq8Ib)
6. serve複數個網站: 如果你想在一個 server 啟多個網站的話。也是可以跳過啦～
   - [How to Host Multiple Websites on One Server](https://www.cloudpanel.io/tutorial/how-to-host-multiple-websites-on-one-server/#steps-to-host-multiple-websites-on-one-server--nginx)
   - [How to Configure Nginx to serve Multiple Websites on a Single VPS](https://webdock.io/en/docs/how-guides/shared-hosting-multiple-websites/how-configure-nginx-to-serve-multiple-websites-single-vps)
7. Install and deploy Multiple Laravel Projects
   - [How to Install and Configure Laravel 8 with Nginx (LEMP) on Ubuntu 18.04](https://www.digitalocean.com/community/tutorials/how-to-install-and-configure-laravel-with-lemp-on-ubuntu-18-04)
   - [How to Deploy A Laravel App With Nginx on Ubuntu(LEMP)](https://www.iankumu.com/blog/how-to-deploy-a-laravel-app-on-lemp-stack/)
8. (optional) 研究關於 Deploy 的其他內容，例如 cloud host 的服務（e.g. Laravel 怎麼上傳檔案到 AWS s3）、實務上架站的方式（https, DNS...）、前後端分離...之類的。
