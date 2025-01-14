# Mở terminal

- ctrl + `

# Tạo lịch sử với git (khởi tạo repository)

- git init

# git add

- ghi vào lịch sử git
- `git add .`: để đưa tất cả các file vào vùng chuẩn bị commit

```bash
git add <path_file1> <path_file2>
```

# git commit

- thêm chú thích cho những file mà mình đã làm vào

```bash
git commit -m"thong tin lich su"
```

# Hiển thị lịch sử làm việc

```bash
git log
# or
git log --oneline
```

# git remote

```bash
git push origin <ten_nhanh>
```

```bash
git branch -v # kiểm tra xem thử đang ở nhánh nào
```

# git clone

# Edit

# Edit 2

# Edit 3

# Edit 4

# Edit 5

# git checkout

## Kiểm tra nhánh đang ở hiện tại

```bash
git branch -v
# or
git branch
```

## Vừa tạo nhánh + nhảy sang làm việc trên nhánh đó

```bash
git checkout -b <ten_nhanh> 
```

## Chuyển nhánh

```bash
git checkout <ten_nhanh_muon_chuyen_sang>
```

## Làm tính năng trang chủ

```bash
git checkout -b feat/home
```
