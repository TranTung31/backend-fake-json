### `I. Các bước cần làm:`
1. Clone code
2. Chạy câu lệnh: npm i
3. Chạy dự án: npm run dev

#### `Lưu ý: Trong trường hợp xóa hết data (file db.json === empty), sử dụng file backup_db.json để lấy dữ liệu`

### `II.Các endpoint (apis) sử dụng:`
```
1. Lấy tất cả blogs:
GET    /blogs

2. Lấy blog theo id
GET    /blogs/:id
GET    /blogs/1

3. Tạo mới 1 blog
POST   /blogs
body truyền lên object { title, author, content}

4. Cập nhật 1 blog
PUT    /blogs/:id
PUT    /blogs/1
body truyền lên object { title, author, content}

5. Xóa 1 blog
DELETE  /blogs/:id
DELETE  /blogs/1