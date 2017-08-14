# LSTM TensorFlow

TensorFlowでLSTM(RNN)を実装する練習です.

---

MNISTデータセットを利用して手書き数字をLSTMで認識するコードを書いた.  
28x28の1行を入力として、その行をシーケンスとして入力データを扱う.

MLP => LSTM => MLP というモデルを構築して学習を行った.  
1段目のMLPはあってもなくても精度に大きな差はなかった.
LSTMの隠れノード数は64だとちょっと精度が下がっていた.

---

LSTMの使い方は理解できたような理解できてないような... :(  
動画認識にLSTMを使おうと思って勉強してるわけだけど、どのようにLSTMに入力を与えるのか、モデルはall in oneなのかseparateなのか、同実装すればいいのかを判断できるほど、機械学習に習熟していないので、CNNだけじゃなくLSTMについても勉強していきたい.
