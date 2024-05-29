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
php artisan make:model Product --table=products
```
-c nếu muốn tạo controller cùng với model
# Controllers
## Tạo controller
```bash
php artisan make:controller ProductController --table=products
```
