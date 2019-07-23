# Khởi tạo repo
```bash
git init
```

# Đặt email với họ tên (dùng chung cho tất cả repo)
```bash
git config --global user.name "họ tên"
git config --global user.email "email@example.com"
```

# Thêm file vào staging area
```bash
# Add 1 file
git add filename
# Add 1 folder
git add src/
```

# Xem trạng thái file
```bash
git status
```

# Tạo commit
```bash
# Commit với message truyền trực tiếp
git commit -m "commit message"
# Commit với message được lấy từ editor
git commit
# Commit đè lên commit gần đây nhất. Trước khi amend có thể git add như bình thường
git commit --amend -m "new commit message"
```

# Xem lại lịch sử commit
```bash
# Xem đầy đủ thông tin của các commit
git log
# Chỉ xem hash và message của các commit
git log --oneline
```

# Xóa file khỏi stagin area
```bash
git rm --cached filename
```

# Tạo và chuyển sang branch mới
```bash
git checkout -b tên-branch
```

# Chuyển sang branch khác
```bash
git checkout tên-branch
```
# Liệt kê các branch
```bash
git branch
```

# Merge
```bash
git checkout branch-đích
git merge branch-nguồn
```

# Thêm remote
```bash
git remote add tên-remote địa-chỉ
```

# Liệt kê remote
```bash
git remote
```

# Push branch lên remote
```bash
git push tên-remote tên-branch
```

