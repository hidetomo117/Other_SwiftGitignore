# Xcodeプロジェクトへの.gitignore追加方法

1 .gitignore作成

	$ cd [your project directory]
	$ touch .gitignore

2 Fiderで隠しファイル表示

	$ defaults write com.apple.finder AppleShowAllFiles true
	$ killall Finder

3 .gitignore編集

	https://github.com/hidetomo117/gitignore/blob/master/Swift.gitignore

4 git管理対象外の設定(すでにコミットしたファイルがある場合のみ)

	$ git rm -r --cached .
	$ git add .
