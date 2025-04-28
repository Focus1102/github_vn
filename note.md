#Terms

- Repository (Repo) //folder làm việc
- Branch //nhánh
- Conflict //xung đột 
- Local //ở máy tính cá nhân
- Remote //ở server

#Commands

- git init //tạo git để làm việc với folder
- git status //kiểm trta trạng thái folder
- git add //add folder vào git
- git reset //hủy add folder
- git commit -m "" //ghi chú lại thay đổi
- git log //kiểm tra ghi chú
- git log --oneline //kiểm tra ghi chú gọn hơn
- git checkout {branch name} //chuyển nhánh
- git branch //kiểm tra đang ở nhánh nào
- git checkout -b {branch name} //tạo một nhánh mới
- git merge {branch name} //gộp code từ nhánh khác vào nhánh đang đứng
- git branch -d {branch name} //xóa nhánh 
- git push //từ local đẩy lên remote
- git pull //đứng nhánh nào kéo code nhánh đó về (remote về local)
- git remote add origin {repo url} //add đường dẫn đến repo trên github
- git push origin {branch name} //đẩy code từ local lên branch trên github
- git clone {repo url} //lấy code từ remote repo github về local
- git fetch origin //làm mới những thay đổi trên (repo url)
- git checkout -b {branch name} origin/{branch name} lấy code từ remote repo url về local (branch name phải giống trên repo url)