# flutter-code-flow
code flow
import 'package:flutter/material.dart';
import 'package:flutter/cupertino.dart';
 void main (){
  runApp(Myapp());



 }

class Myapp  extends StatelessWidget {
  const Myapp({super.key});

  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      theme: ThemeData(primaryColor: Colors.black),
      home: Homepage(

      ),
    );
  }



}
