1. **Chế độ Normal (Command mode):**
    
    - `i`: Chuyển sang chế độ Insert (chèn) trước vị trí con trỏ.
    - `a`: Chèn văn bản sau vị trí con trỏ.
    - `o`: Mở một dòng mới dưới vị trí con trỏ và chuyển sang chế độ Insert.
    - `Esc`: Thoát khỏi chế độ Insert và quay lại chế độ Normal.
2. **Chế độ Insert:**
    
    - `Esc`: Chuyển từ chế độ Insert về chế độ Normal.
3. **Lưu và thoát:**
    
    - `:w`: Lưu (ghi) tập tin.
    - `:q`: Thoát (nếu không có thay đổi).
    - `:wq` hoặc `:x`: Lưu và thoát.
    - `:q!`: Thoát mà không lưu thay đổi.
4. **Di chuyển trong tệp văn bản:**
    
    - `h`: Di chuyển sang trái.
    - `j`: Di chuyển xuống dòng dưới.
    - `k`: Di chuyển lên dòng trên.
    - `l`: Di chuyển sang phải.
5. **Di chuyển nhanh:**
    
    - `G`: Di chuyển đến cuối tệp.
    - `gg`: Di chuyển đến đầu tệp.
    - `:n`: Di chuyển đến dòng thứ n.
6. **Xóa và cắt:**
    
    - `x`: Xóa ký tự tại vị trí con trỏ.
    - `dd`: Xóa dòng hiện tại.
    - `D` hoặc `d$`: Xóa từ vị trí con trỏ đến cuối dòng.
    - `dw`: Xóa một từ từ vị trí con trỏ.
7. **Dán:**
    
    - `p`: Dán nội dung đã được cắt hoặc sao chép dưới vị trí con trỏ.
8. **Thay thế:**
    
    - `r`: Thay thế ký tự tại vị trí con trỏ.
    - `:s/old/new/g`: Thay thế tất cả các xuất hiện của "old" bằng "new" trên dòng hiện tại.
    - `:%s/old/new/g`: Thay thế tất cả các xuất hiện của "old" bằng "new" trong toàn bộ tệp.