# covid-19
報告用
代碼：https://github.com/junaidiqbalsyed/Covid_detection_CNN/blob/master/Covid_detection_using_chest_X_Ray_(Day_2).ipynb
在這個項目中，我們將使用 CNN 進行 Covid-19 檢測，我們將使用的歷史數據是 Covid 胸部 X 片，將使用的預訓練模型是 VGG-16，收到的準確度約為90%
該項目的另一個計劃是可視化 Class Activation maps， Class Activation maps基礎上就是ml算法在最後一個卷積層學到的東西，即如果模型說胸部的圖是COVID-19，使用 GRAD-CAM函數返回熱圖，稍後將其射到輸入的 x 射線上，因此我們可以確定胸部的哪個區域有 COVID-19
