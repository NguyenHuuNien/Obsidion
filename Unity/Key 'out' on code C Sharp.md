Khi bạn khai báo một tham số với từ khóa `out` trong phương thức, nó cho phép phương thức gán giá trị cho tham số đó và truyền giá trị đó ra khỏi phương thức ngay cả khi phương thức không trả về giá trị. Dưới đây là một ví dụ đơn giản:

	using UnityEngine;
	
	public class ExampleScript : MonoBehaviour
	{
	    void Start()
	    {
	        int result;
	        MultiplyByTwo(5, out result);
	        Debug.Log(result); // Kết quả là 10
	    }
	
	    void MultiplyByTwo(int input, out int output)
	    {
	        output = input * 2;
	    }
	}

Trong ví dụ trên, `MultiplyByTwo` là một phương thức không trả về giá trị, nhưng thông qua tham số `out int output`, nó trả về giá trị thông qua biến `output` được truyền từ bên ngoài.