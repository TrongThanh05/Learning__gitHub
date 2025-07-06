# Tools

":Q": quay lại
clear: xóa code

# Terms

Repository
Branch
Conflict
Local
Remote

# Command

- git init: Tạo một repos mới trong folder
- git status: Hiển thị xem files nào đã thay đổi, đã staged hay chưa
- git add <file name>: Thêm file vào staging ("git add. = git add --all" - thêm tất cả files)
- git reset: Không lưu vào staging nữa
- git commit -m "Nội dung commit": Lưu lại các thay đổi vào lịch sử git
- git log: Xem các thời điểm đã lưu
- git log --oneline: gọn hơn của git log
- git checkout <id commit>: quay về commit được đưa vào
- git checkout <branch name>: tới commit hiện tại
- git branch: xem các branch
- git checkout -b <branch name>: Tạo 1 branch mới
- git checkout -d <branch name>: Xóa 1 branch
- git merge <branch name>: tổng hợp 1 branch với branch hiện tại đang chạy
- git push <remote url> <branch name>: Đẩy folder lên github
- git clone <remote url>: tải files trên github về
- git push -u origin <branch name>: đưa branch lên github
- git remote add origin <remote url>
- git push origin <branch name>:
- git fetch origin
- git checkout -b <branch name> origin/ <branch name>: lấy branch trên github về local
- .gitignore file: chứa các files không muốn push lên remote
- Fork: lấy repos của tác giả về account của mình
