# 
# Bài 1: Python là ngôn ngữ thông dịch hay biên dịch? Tại sao?

Python là **ngôn ngữ thông dịch**. Điều này có nghĩa là mã nguồn Python được thực thi trực tiếp bởi trình thông dịch mà không cần phải biên dịch trước thành mã máy. Dưới đây là một số lý do tại sao Python là ngôn ngữ thông dịch:

1. **Thực thi từng dòng một**: Python thực thi từng dòng mã một cách tuần tự. Trình thông dịch đọc và thực thi mã nguồn ngay lập tức, điều này giúp dễ dàng phát hiện và sửa lỗi.
2. **Không cần quá trình biên dịch**: Không giống như ngôn ngữ biên dịch (như C hay C++), Python không cần phải biên dịch trước thành mã máy. Điều này giúp giảm bớt bước chuẩn bị và tăng tốc độ phát triển.
3. **Tính động**: Python là một ngôn ngữ động, có nghĩa là kiểu dữ liệu của biến có thể thay đổi tại thời điểm chạy. Điều này thường dễ dàng hơn để quản lý trong ngôn ngữ thông dịch.

---

### So sánh ngôn ngữ thông dịch và biên dịch (Giải thích dễ hiểu)

**Ngôn ngữ thông dịch** và **ngôn ngữ biên dịch** khác nhau chủ yếu ở cách chúng thực thi mã nguồn:

- **Ngôn ngữ thông dịch**: 
  - Mã nguồn được thực thi trực tiếp từ từng dòng một.
  - Không cần phải biên dịch trước khi chạy.
  - Ví dụ: Python, JavaScript.

- **Ngôn ngữ biên dịch**:
  - Mã nguồn phải được biên dịch thành mã máy (tệp nhị phân) trước khi thực thi.
  - Quá trình biên dịch tạo ra tệp thực thi có thể chạy trực tiếp trên hệ thống.
  - Ví dụ: C, C++.

**Ví dụ cụ thể**:

- **Python (thông dịch)**:
  - Viết mã nguồn Python và chạy trực tiếp bằng cách sử dụng trình thông dịch Python (`python script.py`).
  - Mã sẽ được thực thi từng dòng một, nếu có lỗi ở dòng nào, trình thông dịch sẽ báo lỗi ngay lập tức tại dòng đó.

- **C/C++ (biên dịch)**:
  - Viết mã nguồn C/C++ và phải biên dịch nó thành tệp thực thi 
  - Nếu mã không có lỗi, quá trình biên dịch sẽ tạo ra tệp thực thi (`program`), và ta có thể chạy tệp này trực tiếp.
  - Nếu có lỗi, trình biên dịch sẽ báo lỗi và ta phải sửa mã nguồn, sau đó biên dịch lại.

Tóm lại, **ngôn ngữ thông dịch** thường dễ dàng để bắt đầu và thử nghiệm nhanh chóng, trong khi **ngôn ngữ biên dịch** thường cho hiệu suất cao hơn nhưng cần thêm bước biên dịch trước khi chạy.

---

# Bài 2: Tìm hiểu trước kiến thức buổi 2 về

## Các kiểu dữ liệu trong Python

1. **Kiểu dữ liệu cơ bản**:
   - **Số nguyên (int)**: Số nguyên, ví dụ: `x = 5`
   - **Số thực (float)**: Số thập phân, ví dụ: `y = 3.14`
   - **Chuỗi (str)**: Dãy ký tự, ví dụ: `name = "Hoang"`
   - **Boolean (bool)**: Giá trị đúng/sai, ví dụ: `is_valid = True`

2. **Kiểu dữ liệu phức tạp**:
   - **Danh sách (list)**: Một tập hợp các phần tử, có thể thay đổi, ví dụ: `numbers = [1, 2, 3]`
   - **Tuple (tuple)**: Một tập hợp các phần tử, không thể thay đổi, ví dụ: `coordinates = (10, 20)`
   - **Từ điển (dict)**: Tập hợp các cặp key-value, ví dụ: `student = {"name": "John", "age": 20}`
   - **Set (set)**: Một tập hợp các phần tử duy nhất, ví dụ: `unique_numbers = {1, 2, 3}`

## Các toán tử trong Python

1. **Toán tử số học**:
   - Cộng: `+`
   - Trừ: `-`
   - Nhân: `*`
   - Chia: `/`
   - Chia lấy dư: `%`
   - Lũy thừa: `**`
   - Chia lấy nguyên: `//`

2. **Toán tử so sánh**:
   - Bằng: `==`
   - Khác: `!=`
   - Lớn hơn: `>`
   - Nhỏ hơn: `<`
   - Lớn hơn hoặc bằng: `>=`
   - Nhỏ hơn hoặc bằng: `<=`

3. **Toán tử logic**:
   - Và: `and`
   - Hoặc: `or`
   - Phủ định: `not`

4. **Toán tử gán**:
   - Gán: `=`
   - Gán cộng: `+=`
   - Gán trừ: `-=`
   - Gán nhân: `*=`
   - Gán chia: `/=`

## Mệnh đề điều kiện và vòng lặp

1. **Mệnh đề điều kiện**:
   - `if`:
     ```python
     if dk:
         # code
     ```
   - `elif`:
     ```python
     if dk:
         # code
     elif dk_khac:
         # code
     ```
   - `else`:
     ```python
     if dk:
         # code
     else:
         # code
     ```

2. **Vòng lặp**:
   - `for`:
     ```python
     for pt in ds:
         # code
     ```
   - `while`:
     ```python
     while dk:
         # code
     ```

## Kiểu dữ liệu True, False

- **Boolean (bool)** là kiểu dữ liệu chỉ có hai giá trị là `True` (đúng) và `False` (sai).
- Giá trị boolean thường được sử dụng trong các điều kiện và vòng lặp để kiểm tra các điều kiện logic.
- Ví dụ:
  ```python
  hop_le = True
  if hop_le:
      print("Hop le!")
  else:
      print("Khong hop le!")
  ```


