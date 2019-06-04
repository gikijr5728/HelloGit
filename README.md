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
https://qiita.com/kanaya/items/ad52f25da32cb5aa19e6  
$ git lfs install  
$ git lfs track {LARGE_FILE}            # {LARGE_FILE} を登録
$ git add .gitattributes   
$ git add {LARGE_FILE}                  # 通常のadd  
$ git commit -m 'I added {LARGE_FILE}.' # 通常のcommit  
