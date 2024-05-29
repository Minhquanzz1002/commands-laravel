# Tạo table trong migrations

```
php artisan make:migration create_roles_table
```
## Xóa toàn bộ bảng trong database
```bash
php artisan db:wipe
```

# Models
## Tạo model
Nếu không chỉ định table thì mặc định sẽ tự thêm s vào tên modal
```bash
php artisan make:model Product --table=products -mcfs
```
Trong đó:
- `-mcfs` là các tùy chọn:
  - `-m` tạo Migration cho Model
  - `-c` tạo Controller cho Model
  - `-f` tạo Factory cho Model
  - `-s` tạo Seed cho Model
# Controllers
## Tạo controller
```bash
php artisan make:controller ProductController --table=products
```
