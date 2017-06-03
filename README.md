# Library System
# 測試範圍
* **Login (The number of concurrent users for the stress testing : maximum 1024 users , minimum 2 users.) Submit 2 test scripts)**
    * 請將提供的Login腳本，更改成全部人登入完畢再一起登出。 (check with TA for the sample Login JMeter test script)
    * 一組腳本有設Ramp-up，一組腳本沒設Ramp-up。
    * 請將兩組腳本做一個比較。
      * 有設定Ramp-up的腳本，請在256使用者設為10秒內讓所有使用者皆登入完成。
      * 有設定Ramp-up的腳本，請在512使用者設為20秒內讓所有使用者皆登入完成。
      * 有設定Ramp-up的腳本，請在1024使用者設為40秒內讓所有使用者皆登入完成。
 
* **ISBN Search books (The number of concurrent users for the stress testing : maximum 1024 users , minimum 2 users.) (submit two test scripts, 繳交兩個腳本)**
  * 情境1: 請撰寫一個腳本，利用書本的ISBN號碼進行查詢書本，並等全部人都收尋完畢後，再進行登出。
  * 情境2: 請撰寫一個腳本，等待全部人都登入完成，再進行書本的ISBN號碼查詢書本，並等全部人都收尋完畢後，再進行登出。
    * ISBN請利用JMeter隨機挑選 (Do NOT hard code the ISBN. You may need to write a JavaScript code for selecting the ISBN randomly)。
    * 請將兩組腳本做一個比較。
      * 兩個腳本皆會設定Ramp-up，請在256使用者設為10秒內讓所有使用者皆登入完成。
      * 兩個腳本皆會設定Ramp-up，請在512使用者設為20秒內讓所有使用者皆登入完成。
      * 兩個腳本皆會設定Ramp-up，請在1024使用者設為40秒內讓所有使用者皆登入完成。
* **Check in books / Check out books (The number of concurrent users for the stress testing : maximum 256 users , minimum 2 users.) (submit two test scripts, 繳交兩個腳本)**
  * 情境1 : 請撰寫一個腳本，利用書本的code號碼進行借書和還書，並等全部人都借完和還完後，再進行登出。
  * 情境2 : 請撰寫一個腳本，等待全部人都登入完成，在進行利用書本的code號碼借書和還書，並等全部人都借完和還完後，再進行登出。
  * 書本code請利用JMeter隨機挑選 (Do NOT hard code the book code. You may need to write a JavaScript code for selecting the book code randomly)。
  * 請借完書馬上進行還書，否則會造成其他使用者無法借書。
  * 請將兩組腳本做一個比較。
    * 兩個腳本皆會設定Ramp-up，請在64使用者設為10秒內讓所有使用者皆登入完成。
    * 兩個腳本皆會設定Ramp-up，請在128使用者設為20秒內讓所有使用者皆登入完成。
    * 兩個腳本皆會設定Ramp-up，請在256使用者設為40秒內讓所有使用者皆登入完成。

# 測試方法
Inp 

# 測試終止條件
每個

# 測試環境
* Docker for windows
* Apache Jmeter 3.2
* Win10 64-bits (OS)

# Test Report
**Te**