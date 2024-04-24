> import 'package:flutter/material.dart';

void main() {
  runApp(const MyApp());
}

class MyApp extends StatelessWidget {
  const MyApp({super.key});

  @override
  Widget build(BuildContext context) {
    return MaterialApp( // Bọc ứng dụng bằng MaterialApp
      home: Scaffold( // Sử dụng Scaffold để có nền tảng Material
        body: Container(
          width: 200,
          height: 200,
          color: Colors.green,
          child: const Center( // Thêm Center để căn giữa nội dung
            child: Text(
              'HelloWorld',
              style: TextStyle(fontSize: 24, color: Colors.pink),
            ),
          ),
        ),
      ),
    );
  }
}
