# まずはHTMLとCSSに触れてみる

- 簡単な自己紹介ページを作る  

①ProgateでHTML&CSS初級コースをペアプロでやる  
　Progate=>https://prog-8.com  
　ペアプロとは？=>https://blog.codecamp.jp/programming-pair-advantage-disadvantage  

②問題形式で自己紹介ページを作る（ここからはそれぞれでやるっ）
　Gitで世代管理して、最終的にNetlifyに公開してみる。ってことをします。  
　Gitとは？=>https://www.sejuku.net/blog/5756
Netlifyとは？=>https://qiita.com/TakahiRoyte/items/b7c4d1581df1a17a93fb

　Gitはここからインストール=>http://git-scm.com/download/win  
　「Windows」＋「R」キーを押して、「ファイル名を指定して実行」で「cmd」と入力しOK  

　コマンドプロンプトで「git --version」と入力しバージョンが出力されればおｋ  

　さらに、今回はGihHubというプラットフォームで管理します。（Gitで管理しているソースコードをさらに管理するものだよ。）  
　GitHub=>https://github.co.jp/  
　※似ているものでGitLabというものもあり、どちらもかなり人気だよ。  

　自分のアドレスでアカウントを作成しよう

　新規リポジトリをSelf-introductionという名前で作成しよう  
  これでGitHubの準備は終わり。

　自分の端末上に作業ディレクトいうものを作って、gitの初期設定をしていくよ。  
　以下コマンドをコマンドプロンプトで入力するのだ。  

```
cd C:\
mkdir work
cd work
mkdir Self-introduction
cd Self-introduction
echo "# Self-introduction" >> README.md
dir
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/m0nch1/Self-introduction.git
git push origin master
```

ここまでやったら、GitHubのページを再読み込みしてみよう。  
自分のコミット内容が反映されているよ。  

Gitで世代管理ができるようになったら、問題集.txtを基に自己紹介ページを作成しよう！  

※１問題を解くごとに一回コミットしてみよう。  
コミット例を以下に示すぞ。  
この例は、問題１を解いた後の場合ね。  
コミットしたらGitHubのページをまた再読み込みしてみよう！
```
git add index.html  //git add でコミット対象のファイルを指定する
git commit -m "titleの変更" //git commit -m でコミットメッセ―ジを決めるよ
git push origin master // git push で作成したコミットをリモートのリポジトリにコミットするよ
```

③Netlifyにデプロイする！（Web公開する！）
https://www.netlify.com/にアクセスして、さっき作ったGitHubアカウントでLog inする！

New site from gitクリック

Continuous DeploymentではGitHubを選択

さっき作ったリポジトリ（Self-introduction）を選択！
++
Deploy siteをクリック！

終  
制作・著作  
━━━━━  
ⓃⒽⓀ  

# Javascriptにも触れてみる?

# Wordpressでスムージーの紹介ページを作ってみる！