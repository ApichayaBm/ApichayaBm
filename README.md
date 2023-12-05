import 'package:flutter/material.dart';

void main() {
  runApp(MyApp());
}

class MyApp extends StatelessWidget {
  //const MyApp({super.key});
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      home: Scaffold(
        appBar: AppBar(
          title: Text('Apichaya Thassamalee'),
          centerTitle: true,
        ),
        body: Center(
          child: Text(
            'ชื่อ: อภิชญา ทัศมาลี\nรหัสนักศึกษา: 640710149',
            style: TextStyle(
              fontSize: 24.0,
              fontWeight: FontWeight.bold,
              color: Colors.deepPurpleAccent, 
            ),
            textAlign: TextAlign.center,
          ),
        ),
      ),
    );
  }
}
