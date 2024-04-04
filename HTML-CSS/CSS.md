## Internal
Thẻ Styte để viết css
h1{
	color: red;
	font-size: 20px;
}
## External
- tạo file css riêng và link vào
## Inline
- thêm trực tiếp vào thẻ

# ID/Class
- id: chỉ có 1 (#)
- class: nhiều nhóm được (.)

# Mức độ ưu tiên
!importain - Inline - id - class - tag
# Tên biến
:root{
	--name-value: green
}
gọi đến biến: var(<tên biến>)
# Đơn vị
- px - tính theo đơn vị pixel
- % - tính theo giá trị tương đối so với thẻ chứa nó
- vw/vh - tính theo màn hình viewport wight, viewport hight
- rem - dựa trên tag html
- em - dựa trên thẻ chứa nó gần nhất