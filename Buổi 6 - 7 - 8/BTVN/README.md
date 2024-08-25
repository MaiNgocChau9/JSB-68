# Thẻ Form trong HTML

#### Cú pháp thẻ `form`:

```html
<form action="" method="">
    <!-- Các thẻ item của form -->
</form>
```

#### Các thẻ item trong form

* `input`

  - `text`: Cho phép nhập dữ liệu là text
  - `password`: Nhập dữ liệu là mật khẩu
  - `number`: Chỉ cho phép nhập dữ liệu là số
  - `radio`: Cho phép tạo những lựa chọn trên form (chỉ được phép chọn 1 trong nhiều lựa chọn còn lại)
  - `checkbox`: Cho phép tạo ra lựa chọn và có thể chọn nhiều
  - `date`: Cho phép chọn ngày tháng năm
  - `email`: Chỉ cho phép nhập dữ liệu có định dạng là email
  - `file`: Cho phép chọn file
* Thuộc tính của thẻ `input`

  - `id`
  - `class`
  - `name`
  - `value`
  - `size`: Đơn vị là số, quy định chiều dài của input
  - `placeholder`: Dùng để mô tả cho input đó

---

* `label`
  Giúp mô tả thông tin cho một input

---

* `button`
  Có các type sau

  - submit: Gửi thông tin lên server để xử lý
  - reset: Xóa hết thông tin đã nhập trên form

---

* `select`

  ```html
  <select>
      <option value="">Label name</option>
  </select>
  ```

---

* `textarea`

  ```html
  <textarea rows="giá trị số" cols="Giá trị số"></textarea>
  ```

---

* `fieldset`

  - Tạo ra ô bọc cho form
  - Bên trong thường sử dụng thêm thẻ legend
