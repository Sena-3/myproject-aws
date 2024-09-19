# 第２回講座の感想
## 何日間EC2インスタンス内で作業してGit push できるまで時間がかかりかなり衝撃的でした。
ここでEC2インスタンス内でのgitの使い方やコマンドラインが未知で調べて調べてもエラーだらけでしたが今は少し分かって来ました。
>
GitのコマンドをEC2インスタンス内で習ったコマンドライン:
1. repositoryをローカルPCにクローンする　git clone http://？？？
2. リポジトリへ移動する　cd "repository-name"
3. ブランチをチェックする　git branch *付いているところは今のブランチ
4. Git ブランチ作る　git branch branch-name
5. ファイルをチェックするコマンド　ls
6. ブランチへ移動する　git checkout branch-name
7. ファイルの作成 touch file-name.md
8. ファイルのステージング git add file-name.md
9. git commit -m "add file-name.md"
10. ステージング情報のプッシュ git push origin branch-name
11. など、、
>
これからももっとコマンドを知り操作できるよう頑張って習い続けます。
