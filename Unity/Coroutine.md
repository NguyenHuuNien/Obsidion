# Gọi đến Coroutine
- Sử dụng StartCoroutine(..) để gọi đến hàm sử dụng
- Hàm được Coroutine  gọi là hàm trả về kiểu IEnumerator với kiểu trả về là yield return

`IEnumerator Fade()
{
    for (float ft = 1f; ft >= 0; ft -= 0.1f)
    {
        Color c = renderer.material.color;
        c.a = ft;
        renderer.material.color = c;
        yield return null;
    }
}`
Hàm sẽ được gọi trong 1 fame từ 1-2 lần
Chương trình sẽ thực hiện trong vòng for và mỗi khi gặp `yield return` thì sẽ lưu thời điểm đang hoạt động lại để fame sau tiếp tục thực hiện.
> Chú ý: Coroutine không có kiểu dữ liệu để trả về

# Một số loại yield hay sử dụng:

- **yield WaitForSeconds**: tiếp tục thực thi sao một khoảng thời gian, sau Update của frame đó.
- yield WaitForFixedUpdate: tiếp tục thực thi sau tất cả FixedUpdate đã được thực thi.
- **yield WWW**: thực thi sau khi WWW downloads hoàn tất.
- yield StartCoroutine(…): thực thi sau khi coroutine trong hàm này hoàn thành trước.
- Tự tạo một loại **YieldInstruction** implement từ CustomYieldInstruction
- yield WaitForSecondsRealtime (timeScale luôn = 1), yield WaitUntil, yield WaitWhile…