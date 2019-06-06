# Computer Vision Homework 6
## ORB-SLAM 2 Implementation
我們這組這次只利用了老師提供的github完成場景的追蹤，Monocular Augmented Reality的介面我們嘗試很久還是沒辦法將GUI開啟，並且插入物件。
ORB-SLAM2場景追蹤的部分，我們用了兩部影片做測試。第一部是在山路滑板高速行駛的影片，第二部是我們宿舍房間的影片。第二部影片特徵點的偵測與場景追蹤的效果比第一部影片來的好，我們認為是因為第一部影片因為移動速度太快導致畫面模糊，特徵點的數量不夠。
### Input Videos
* Video 1 (our video)

https://drive.google.com/file/d/1rmiVxwDKESd2muCS_gT58IRZy2DzhHPw8w/view

* Video 2 (from Youtube)

https://drive.google.com/open?id=1W1c0h5LJG-nc259-Rkglch8qHqUIyapX

### Results
* Result 1
* 
![](https://i.imgur.com/QPi32Tt.gif)

* Result 2
* 
![](https://i.imgur.com/949tIv9.gif)

## Visual Effect with Post-production Software
我們使用威力導演的動態追蹤的功能實作，使用滑板的影片做為 input video
1. 我們以滑板玩家的鞋子及滑板做為追蹤的物件(較穩定，不會時有時無)

![](https://i.imgur.com/w8zsGbC.jpg)

2. 追蹤的狀況

![](https://i.imgur.com/0Vd35ad.png)
![](https://i.imgur.com/LQkaUCs.png)
![](https://i.imgur.com/byjS2r5.jpg)

3. 加入簡單文字，匯出最後的結果影片

https://drive.google.com/open?id=198mPlgmfEFScyY0T3eIU66jhL7EzyobJ
