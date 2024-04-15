# udacity
[My GitHub Profile](https://github.com/chuonchuon9x/udacity)

Branch Management
1. git branch
Description: Liệt kê tất cả các nhánh hiện có trong kho lưu trữ.
Syntax:
bash
Copy code
git branch
2. git checkout
Description: Chuyển đổi sang một nhánh khác hoặc khôi phục các thay đổi từ nhánh khác.
Syntax:
bash
Copy code
git checkout <branch-name>
3. git merge
Description: Hợp nhất một nhánh khác vào nhánh hiện tại.
Syntax:
bash
Copy code
git merge <branch-name>
Remote Management
1. git remote
Description: Hiển thị danh sách các remote đã được thiết lập cho kho lưu trữ.
Syntax:
bash
Copy code
git remote -v
2. git fetch
Description: Lấy tất cả các thay đổi từ remote nhưng không thực hiện hợp nhất.
Syntax:
bash
Copy code
git fetch <remote-name>
3. git pull
Description: Kéo các thay đổi mới nhất từ remote và hợp nhất chúng vào nhánh hiện tại.
Syntax:
bash
Copy code
git pull <remote-name> <branch-name>
4. git push
Description: Đẩy các commit cục bộ lên remote.
Syntax:
bash
Copy code
git push <remote-name> <branch-name>
History and Changes
1. git log
Description: Hiển thị lịch sử các commit trong kho lưu trữ.
Syntax:
bash
Copy code
git log
2. git revert
Description: Tạo một commit mới để hoàn tác các thay đổi của một commit cụ thể.
Syntax:
bash
Copy code
git revert <commit-hash>
3. git cherry-pick
Description: Chọn một commit từ một nhánh và áp dụng nó vào nhánh hiện tại.
Syntax:
bash
Copy code
git cherry-pick <commit-hash>