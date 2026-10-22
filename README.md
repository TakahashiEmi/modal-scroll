#### 2026-05-21  
ファイル構成  
>main.php　　　　　　メイン  
>admin-input.php　　管理画面のUI  
>modal.html　　　　　フロント側（html+js)  
>style.css　　　　　　フロント  

main.php  
&ensp;管理画面に「モー脱画像」メニューを追加  
&ensp;POST値をサニタイズしてwp_optionに追加  
&ensp;東光記事にアクションフックでモーダルを追加  

admin-input.php  
&ensp;管理画面の中身のhtml  
&ensp;フィールド初期値に入力値を表示  
&ensp;form送信  

modal.html  
