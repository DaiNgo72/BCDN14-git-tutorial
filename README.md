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

- download source code về

```bash
git clone <duong_dan_source_code>
```

# Edit

# Edit 2

# Edit 3

# Edit 4

# Edit 5

# Mai Dang Huy đã ở đây

# Edit 6

# Mai Dang Huy da roi di

# test stash

# Edit 7 - kiet

# Demo luc 20250110

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

# git merge

- Nhảy sang nhánh mà mình muốn merge code

```bash
git merge <ten_nhanh_muon_them_vao_nhanh_hien_tai>
```

## Merge nhánh feat/home và nhánh master

```bash
git checkout master
git merge feat/home
```

# Pull nhánh master về và merge vào nhánh feat/home

```bash
git pull origin master
```
