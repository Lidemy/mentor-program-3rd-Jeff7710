## 交作業流程


1. 新開一個 branch，假設叫做 Week_1 `git branch Week_1`
2. 切到寫作業的 branch `git checkout Week_1`
3. 開始寫作業，寫完後把結果 push 上 Github，且發 pull request `git push origin Week_1`
4. 貼連結到交作業專用的 repository 發一個 issue（要按照發文格式）
5. 這時胡立會 merge branch，把 branch 刪除，close issue
6. 之後切到 master 的 branch，把改完作業的 branch pull 下來 `git pull origin master`
7. 把 Week_1 的 branch 刪掉 `git branch -d Week_1`