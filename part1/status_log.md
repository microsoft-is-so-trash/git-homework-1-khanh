On branch main
Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
	deleted:    ../README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	./

no changes added to commit (use "git add" and/or "git commit -a")
=== 6. Difference between `git fetch` and `git pull` ===
- `git fetch`: Tải các commit và branch mới nhất từ remote về local repo dưới dạng remote-tracking branch (origin/main), không làm thay đổi trực tiếp file trong thư mục làm việc.
- `git pull`: Tải dữ liệu mới về và tự động gộp (merge) thẳng vào branch hiện tại của local.
