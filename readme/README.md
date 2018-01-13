# Azure Feedback

## 一開始註冊時

![image](https://github.com/andylinandylin/azure-feedback/blob/master/img/register.gif)

 * 註冊介面大致清楚
 * 因為區域的不同，有的機器種類不一樣，我們需要選擇美國東北才找的到我們要的機器
 * Resouce Group選項我們似乎用不太到，但是只刪除機器重新註冊時，舊的Group不會一起被刪掉

## 剩餘用量查詢

![image](https://github.com/andylinandylin/azure-feedback/blob/master/img/subscription.png)

![image](https://github.com/andylinandylin/azure-feedback/blob/master/img/0.jpg)

 * 這是最大的問題，使用機器後，剩餘用量不會減少
 * 只有在用了很多甚至是用光的時候，才會顯示
 * 但是當助教幫我們儲值後，使用機器，剩餘用量還是一直保持一樣沒有減少
 * 圖中是使用很久之後，估計剩餘金額應該已經少於100，但剩餘用量還是一直沒有減少
 * 所以常會遇到直接就被停用，資源使用殆盡的情況
 * 這樣會很難估計是否快用完，甚麼時候需要再儲值或是盡快把檔案先從機器取出來

## 使用時須注意事項

![image](https://github.com/andylinandylin/azure-feedback/blob/master/img/shutdown.png)

 * 需要非常小心，一定必須記得關機，說了三次，肯定很重要
 * 不然資源會在甚麼事都沒做的情況下消耗殆盡
 * 也許可以有一點防呆機制，類似電腦的休眠之類的功能，避免資源的浪費
 
## 使用GPU心得

 * 整體而言使用起來很滿意
 * 有時會有抓不到GPU的問題，但沒有甚麼是下面這行指令解決不了的
```
sudo reboot
```
 * GPU K80 11G 速度夠快，且GPU記憶體11G很足夠是最大的優點
 * 虛擬機器的環境可以自由運用並且在ubuntu環境下安裝任何想要的套件，比起有些公司只提供GUI的GPU資源還彈性很多
 * 因為虛擬機器可能都要一小段時間安裝一些基本套件，建議可以送一點免費資源先讓使用者setup
 * 最後感謝微軟超佛心公司的100份茶點及100份pizza
 * 整體Azure使用心得我給超過100分~

![image](https://github.com/andylinandylin/azure-feedback/blob/master/img/thanks.gif) 
 