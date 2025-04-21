import 'package:flutter/material.dart';
void main() => runApp(MyApp());
class MyApp extends StatelessWidget {
 @override
 Widget build(BuildContext context) {
 return MaterialApp(
 home: ColorContainerDemo(),
 );
 }
}
class ColorContainerDemo extends StatelessWidget {
 @override
 Widget build(BuildContext context) {
 return Scaffold(
 appBar: AppBar(title: Text('Container with Color')),
 body: Center(
 child: Container(
 width: 150,
 height: 150,
 color: Colors.teal, // ⬅️ Color property
 ),
 ),
 );
 }
}
