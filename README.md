# TemperatureControlExperiment
釧路高専 専攻科 2S 特別演習 電気工学分野 温度制御実験

### コンパイル方法
```
platex report && platex report && dvipdfmx report  
```

### ブランチの作成方法
あなたの名前がyournameで、section1の編集をするブランチを作成するとき
```
git checkout -b yourname_section1
```
```
git push -u origin yourname_section1
```

### 作業内容をアップロードする
yourname_section1ブランチに作業内容を反映させるとき
```
git add .
```
```
git commit -m "feat: section1を追加"
```
```
git push -u origin yourname_section1
```
担当している章が完成したら、GitHubでプルリクを作成してください。

### 作業ブランチを既存のブランチに変更する方法
```
git checkout 既存のブランチ名
```