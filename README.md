# MachineLearning-100Days-Review-
My noted for Machine-Learning-100-Days


## 目錄
程式目錄	IV
### 第一章 Python 安裝及快速入門	1
- 1-1 Python 安裝	1
- 1-2 Python 快速入門	1
### 第二章 資料匯入、預視及Pandas	6
- 2-1  Pandas DataFrame	6
- 2-2  Pandas 建立/讀取資料	7
- - 2-2.1利用pd.DataFrame函式創立dataframe	7
- - 2-2.2使用Pandas 匯入資料	7
- 2-3  預視資料 及 繪圖	8
- - DataFrame -- Pandas	8
- - 2-3.1連續型變數 預視 (含基礎迴圈for)	10
- - 2-3.2類別型變數 預視 (含基礎聚集def)	12
- - 2-3.3資料分組 預視	14
- 2-4  多個資料合併 merge / transform	20
### 第三章 格式化資料 【資料預視、預處理及 Sklearn】	22
- 3-1  建立/讀取資料補充- Copy	28
- 3-2  特徵工程範例	29
- - 3-2.1範例1：鐵達尼號的乘客生存預測 (binary classification: LogisticRegression)	29
-  - Day017 什麼是Titanic dataset?  	29
-  - 數值型特徵	31
-  - 類別型特徵	37
-  - 特徵選擇	44
-  - 補充	51
- - 3-2.2範例2：計程車費率預測 (LinearRegression)	55
- - 3-2.3範例3：鳶尾花辨識(multi-classification: KNeighborsClassifier & 樹狀模型)	60
- 3-3超參數 (Hyper-paramter)調整與優化	68
- - 實戰練習 - Enron Fraud Dataset 安隆公司詐欺案資料集	69
- 3-4  非監督式學習及Sklearn	78
- - 3-4.1聚類算法Clustering: K-means	78
- - 3-4.2類算法Clustering: 階層式分群Hierarchical Clustering	88
- - 3-4.3降維方法 - 主成份分析 (PCA)	94
- - 3-4.4降維方法 - t-SNE	99
### 第四章 圖片資料 【初探深度學習使用Keras】	103
- 4-1 讀取檔案：txt檔 & 圖片檔	103
- - 讀圖檔的三種方法	104
- - 圖檔的資料結構：矩陣中的數字代表的意義	105
- - 情境練習：讀取 txt檔案中的圖片連結	106
- - 補充說明: resize	108
- 4-2 Keras資料庫	109
- 4-3 資料前處理	111
- - STEP1. 載入套件	111
- - STEP2.1資料預視	111
- - STEP2.2資料預處理之概念	112
- - STEP3設定模型與運算 (DNN vs. CNN / plus ImageDataGenerator)	113
-  - 實務情境上補充說明 – 資料量過大或過小的處理技巧	116
- 4-4深度神經網路及多層感知(Multi-layer Perception, MLP)	123
- - 執行程序藍圖與體驗	125
- - 4-4.1 步驟一：選擇模型	128
-  - 4-4.1.1 序列模型搭建網路(Keras Sequential API)	128
-  - 4-4.1.2 函數式模型搭建網路(Functional API (or Model))	129
-  - 4-4.1.3多層感知(Multi-layer Perception, MLP)	131
- - 4-4.2 步驟二：建構網路層	132
-  - 4-4.2.1 激活函數(Activation Function)	132
-  - 4-4.2.2 正規化(Regularization)	134
- - 4-4.3 步驟三：編譯	136
-  - 4-4.3.1 損失函數(Loss Function)	136
-  - 4-4.3.2 優化(Opimizer)	139
-  - 4-4.3.3 梯度調整(Gradient Descent)：優化器的參數調整	143
- - 4-4.4 訓練、預測模型範例	149
-  - 4-4.4.1 Optimizers & Learning rates (D080練習)	149
-  - 4-4.4.2 正規化(D084練習)	152
- - 4-4.4.3 callbacks 函數	154
- 4-5傳統電腦視覺提取特徵的方法：color histogram 及HOG 特徵	157
- 4-6卷積神經網路Convolution Neural Network_CNN	158
- - 濾波器 (filter)的概念	158
- - 卷積網路的組成	159
-  - 1. Convolution Layer 卷積層	159
-  - 2. Pooling Layer 池化層	161
-  - 3. Flatten Layer 平坦層	162
-  - 4. Fully connection Layer 全連接層	162
-  - 5. 回顧--卷積神經網路(CNN)特性	162
- - 程式架構範例	163
- - 隨堂小考	164
- 4-7 Keras 中的 CNN layers -- Conv2D	165
- 4-8 遷移學習(Transfer Learning) -- ResNet	166
- 4-9 Kaggle資料實戰練習 --花朵辨識	168
- - 範例解答 - 方法一 (ImageDataGenerator)	169
- - 範例解答 - 方法二 (ImageDataGenerator +ResNet50)	173
### 附錄 網路學習資源	177


