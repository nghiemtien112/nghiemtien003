import 'package:flutter/material.dart';

void main() {
  runApp(const MyApp());
}

class MyObject {
  int value;

  MyObject({
    required this.value,
  });

  // Phương thức tăng giá trị
  void increase() {
    value++;
  }

  // Phương thức giảm giá trị
  void decrease() {
    value--;
  }

  // Phương thức đặt giá trị
  set setValue(int newValue) {
    value = newValue;
  }
}

class MyApp extends StatefulWidget {
  const MyApp({Key? key}) : super(key: key);

  @override
  State<MyApp> createState() => _MyAppState();
}

class _MyAppState extends State<MyApp> {
  MyObject myObject = MyObject(value: 0);
  String? title;

  Widget _buildText() {
    return Text(
      'Giá trị: ${myObject.value}',
      style: const TextStyle(fontSize: 20),
    );
  }

  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      home: Scaffold(
        appBar: AppBar(
          leading: const Icon(Icons.person),
          title: Text(title ?? 'Debugging App'),
        ),
