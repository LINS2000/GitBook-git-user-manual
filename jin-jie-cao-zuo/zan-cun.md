# 暫存 -- Stash

---

若想要切換不同分支，工作區域中檔案的必須是乾淨的，意即所有已異動的檔案須先儲存\(Commit\)或回復\(Revert\)，但若想保留異動又不想做Commit或Revert時，可以使用暫存\(Stash\)功能。

\(1\)    滑鼠右鍵→選`Stash Save`

![](/assets/stash--01.png)

\(2\)    填寫Stash Message，可任意輸入一些文字

![](/assets/stash--02.png)

\(3\)    暫存成功

![](/assets/stash--03.png)

\(4\)    檢視版本分支圖\(Revision Graph\)，該分支多出一支stash分支

![](/assets/stash--04.png)

\(5\)    當其他事情處理完切回原本分支，想取回暫存資料，滑鼠右鍵→選`Stash Pop`

![](/assets/stash--05.png)

\(6\)    檢視版本分支圖\(Revision Graph\)，stash分支已消失

![](/assets/stash--06.png)

