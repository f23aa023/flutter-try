5/20

``` Dart
import 'package:flutter/material.dart';

void main() {
  runApp(const MyApp());
}

class MyApp extends StatelessWidget {
  const MyApp({super.key});

  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      title: 'Flutter Demo',
      home: Scaffold(
        appBar: AppBar(
          title: Text('Hello, flutter!')
        ),
        body:Text(
         'Hello, Flutter World!!',
         style: TextStyle(fontSize: 32.0),
        ),
      ),
    );
  }
}
```

とりあえず何か書きたいならScaffoldを使えばよいということは分かった   
コード云々よりもgithubの使い方がいまいちわからなくて、慣れる必要がありそうです
