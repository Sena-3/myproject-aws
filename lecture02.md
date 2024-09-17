# 第２回講座の感想
## 何日間EC2インスタンス内で作業してGit push できるまで時間がかかりかなり衝撃的でした。
ここでEC2インスタンス内でのgitの使い方やコマンドラインが未知で調べて調べてもエラーだらけでしたが今は少し分かって来ました。
>
1. GitのコマンドをEC2インスタンス内で習ったコマンドライン:
2. repositoryをローカルPCにクローンする　git clone http://？？？
3. リポジトリへ移動する　cd "repository-name"
4. ブランチをチェックする　git branch *付いているところは今のブランチ
5. Git ブランチ作る　git branch branch-name
6. ファイルをチェックするコマンド　ls
7. ブランチへ移動する　git checkout branch-name
8. ファイルの作成 touch file-name.md
9. ファイルのステージング git add file-name.md
10. git commit -m "add file-name.md"
11. ステージング情報のプッシュ git push origin branch-name
12. など、、
>
これからももっとコマンドを知り操作できるよう頑張って習い続けます。
