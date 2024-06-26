# Orientação a Objetos e UML: Diagramação de Classes do iPhone

Este é um diagrama UML que representa a estrutura de classes e interfaces para um sistema que inclui a modelagem do iPhone, um dispositivo que incorpora funcionalidades de um reprodutor de música, um telefone e um navegador de internet. Este diagrama foi criado como parte do desafio de projeto do **SSantander 2024 - Backend com Java** na DIO.me.

## Diagrama UML

O diagrama UML pode ser visualizado na imagem abaixo:
![Diagrama ](diagrama.png)

## Descrição das Interfaces e Classes

### Reprodutor Musical (MusicPlayer)

A interface `MusicPlayer` é responsável por implementar a funcionalidade de reprodução de música. Ela possui métodos como `playMusic()`, `pauseMusic()`, e `stopMusic()`.

### Aparelho Telefônico (Telephone)

A interface `Telephone` é responsável por implementar a funcionalidade de um telefone. Ela possui métodos como `makeCall(String phoneNumber)`, `endCall()`, e `receiveCall()`.

### Navegador de Internet (InternetBrowser)

A interface `InternetBrowser` é responsável por implementar a funcionalidade de um navegador web. Ela possui métodos como `openWebsite(String url)`, `refreshPage()`, e `bookmarkPage(String url)`.

### iPhone

A classe `iPhone` implementa as interfaces `MusicPlayer`, `Telephone`, e `InternetBrowser`, reunindo todas as funcionalidades em um único dispositivo.
