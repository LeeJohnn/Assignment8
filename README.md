這次的Lab利用助教給的Socket_sample來完成，首先在原本的Socket裡的MainActivity加上Lab10的計算機，並更改.xml檔案，還有在一開始ip_page的地方，當按下OK時就Jump到
activity_main，也就是計算機的畫面，而當按下加、減、乘或除時MainActivity裡的Thread start並傳入result，利用PrintWriter將output傳給Server，並在Server端印出result。