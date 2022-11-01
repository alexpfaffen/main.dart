# main.dart

import 'package:flutter/material.dart';

void main() {
  runApp(MaterialApp(
    home: Scaffold(
      appBar: AppBar(
        title: Text('Primeiro App'),
    ),
    body: Center(
      child: Text('Olá Mundo', style: TextStyle(
        color: Colors.blueGrey,
        fontSize: 22.0,
        fontWeight: FontWeight.bold
      ),),
     ),
    )
  ));
} 
