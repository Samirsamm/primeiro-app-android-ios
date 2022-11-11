# primeiro-app-android-ios
Este repositório contém o meu primeiro desenvolvimento mobile.
import 'package:flutter/material.dart';

void main() {
  runApp(
    MaterialApp( // O MaterialApp é a fundação para todos os widghets que iremos mostrar na tela.
      home: Scaffold(
        backgroundColor: Colors.blueGrey[900], //Mudando a cor de fundo da barra do App
        appBar: AppBar(
          backgroundColor: Colors.blueGrey[700], //Mudando a cor de fundo do app
          title: Text('Eu Sou Rico'), //Texto da barra superior
        ),
        body: Center( //O corpo do aplicativo etá sendo ajustado para o centro
            child: Image(
              image: AssetImage('imagens/rubi.png'), //Pegando uma imagem do AssetImage, que acessa a pasta imagens do projeto.
            ),
        ),
      ),
    ),
  );
}
