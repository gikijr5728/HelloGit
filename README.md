# HelloGit
初めてのGitHub  

#GitHubの覚書  
・リポジトリのクローン  
git clone http://リポジトリのurl/プロジェクト名.git  
  
・CRLFのエラー回避  
git config --global core.autoCRLF false
  
・リポジトリの追加方法  
1）変更をインデックスに追加  
$ git add test.txt  

2）ファイルを登録（コミット）  
$ git commit -m "変更してみたよ"  
  
3）データの送信  
$ git push origin master  

# でかいファイルのアップロード
