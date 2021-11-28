開発に至った背景

このアプリはローソク足のパータンを分析するために開発した。使用したプログラミング言語はJAVAだ。
まず、ローソク足は1本で一定期間における株価の値動きを表したものだ。
ローソク足は一定期間内で取引された4つの株価を表す。それは始値（期間中で最初に取引された値段）、終値（期間中で最後に取引された値段）、高値（期間中で最も高く取引された値段）と　安値（期間中で最も安く取引された値段）だ。
ローソク足を参考して過去のデータや相場の動きを一目で読み取れて、株価のトレンドを把握できる。
多くの人にローソク足チャットを使って株価を分析できるようになるためにこのアプリを開発した。
使用者はアプリを使うことで、株価データ倉庫から三つの特定ローソク足のパータン(1.首吊り線,2.黒三兵,3.弱気の放れ三手)を簡単に見つけることができる。
まず、株価データ倉庫(table.csv)をダウンロードして、株価データ倉庫とコードを同じフォルダに保存して、コンソールでアプリを実行する。
使用者は提供された日付き（19/11/2012-17/11/2017)から探している日付とローソク足パータンを入力して、条件に合う株価が表示される。
例えば、入力内容：
javac Stock_Price_Pattern.java  
java Stock_Price_Pattern.java 2012-12-12 2015-12-12

 ---Please input your opiton--- 
 1. Hanging Man 
 2. Three Black Craws 
 3. Bearish Kicker 
 4. Quit
 ------------------------------ 
Input: 1
Pattern Found: 2013-04-05
Pattern Found: 2013-08-22
Pattern Found: 2014-06-18
Pattern Found: 2014-10-21
Pattern Found: 2014-11-28
Pattern Found: 2015-02-13
Pattern Found: 2015-07-01


今後の改善点
UI(ユーザーインターフェース)のデザインには改善の余地がある。
１。パターンの説明をインターフェースに追加することができる。
２。日付の範囲をインターフェースに追加することができる.

