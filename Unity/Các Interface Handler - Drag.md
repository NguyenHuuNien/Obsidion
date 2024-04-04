1. **IBeginDragHandler**: Interface này được triển khai để xử lý sự kiện khi một đối tượng bắt đầu được kéo (drag). Phương thức `OnBeginDrag` được gọi khi sự kiện này xảy ra.
    
2. **ICancelHandler**: Interface này được triển khai để xử lý sự kiện khi một thao tác bị hủy bỏ. Phương thức `OnCancel` được gọi khi sự kiện này xảy ra.
    
3. **IDeselectHandler**: Interface này được triển khai để xử lý sự kiện khi một đối tượng bị bỏ chọn (deselect). Phương thức `OnDeselect` được gọi khi sự kiện này xảy ra.
    
4. **IDragHandler**: Interface này được triển khai để xử lý sự kiện khi một đối tượng đang được kéo (drag). Phương thức `OnDrag` được gọi khi sự kiện này xảy ra.
    
5. **IDropHandler**: Interface này được triển khai để xử lý sự kiện khi một đối tượng được thả vào (drop). Phương thức `OnDrop` được gọi khi sự kiện này xảy ra.
    
6. **IEndDragHandler**: Interface này được triển khai để xử lý sự kiện khi một đối tượng kết thúc việc kéo (drag). Phương thức `OnEndDrag` được gọi khi sự kiện này xảy ra.
    
7. **IEventSystemHandler**: Interface này là giao diện cơ bản cho tất cả các handler sự kiện trong hệ thống sự kiện của Unity.
    
8. **IInitializePotentialDragHandler**: Interface này được triển khai để xử lý sự kiện khi một đối tượng có khả năng bắt đầu kéo (drag). Phương thức `OnInitializePotentialDrag` được gọi khi sự kiện này xảy ra.
    
9. **IMoveHandler**: Interface này được triển khai để xử lý sự kiện khi một đối tượng di chuyển. Phương thức `OnMove` được gọi khi sự kiện này xảy ra.
    
10. **IPointerClickHandler**: Interface này được triển khai để xử lý sự kiện khi một điểm nhấn chuột được thực hiện. Phương thức `OnPointerClick` được gọi khi sự kiện này xảy ra.
    
11. **IPointerDownHandler**: Interface này được triển khai để xử lý sự kiện khi một điểm nhấn chuột xuất hiện. Phương thức `OnPointerDown` được gọi khi sự kiện này xảy ra.
    
12. **IPointerEnterHandler**: Interface này được triển khai để xử lý sự kiện khi con trỏ chuột đi vào khu vực của một đối tượng. Phương thức `OnPointerEnter` được gọi khi sự kiện này xảy ra.
    
13. **IPointerExitHandler**: Interface này được triển khai để xử lý sự kiện khi con trỏ chuột rời khỏi khu vực của một đối tượng. Phương thức `OnPointerExit` được gọi khi sự kiện này xảy ra.
    
14. **IPointerUpHandler**: Interface này được triển khai để xử lý sự kiện khi một điểm nhấn chuột kết thúc. Phương thức `OnPointerUp` được gọi khi sự kiện này xảy ra.
    
15. **IScrollHandler**: Interface này được triển khai để xử lý sự kiện cuộn. Phương thức `OnScroll` được gọi khi sự kiện này xảy ra.
    
16. **ISelectHandler**: Interface này được triển khai để xử lý sự kiện khi một đối tượng được chọn (select). Phương thức `OnSelect` được gọi khi sự kiện này xảy ra.
    
17. **ISubmitHandler**: Interface này được triển khai để xử lý sự kiện khi một biểu mẫu được gửi đi (submit). Phương thức `OnSubmit` được gọi khi sự kiện này xảy ra.
    
18. **IUpdateSelectedHandler**: Interface này được triển khai để xử lý sự kiện khi đối tượng được cập nhật là đối tượng được chọn. Phương thức `OnUpdateSelected` được gọi khi sự kiện này xảy ra.