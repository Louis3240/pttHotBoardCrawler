跟Vue_Homework類似這個專案是整合Laravel、Curl、Xpath的練習，新加了可以抓取PTT的熱門看版

需有資料庫和laravel才能完成

照如下指示即可成功

1.先解壓縮到喜歡的位置

2.麻煩先建個資料庫ptt(本人是用XAMPP到phpmyadmin直接下指令)
create database ptt default character set utf8

3.接著cmd繼續下指令，將資料表欄位建好
php artisan migrate

4.打開連接(我是用Mysql，在XAMPP裡面打開)，並下以下指令
php artisan serve

5.就可以到以下網址看結果(一開始應該是沒有資料，可以點擊黃色星星按鈕抓PTT資料))
127.0.0.1:8000