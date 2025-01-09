iPhone Functionalities Implementation

This project demonstrates the implementation of the core functionalities of an iPhone, inspired by its 2007 launch presentation. The features include a Music Player, Phone functionality, and an Internet Browser.

Features

1. Music Player

Methods:

tocar() - Play a song.

pausar() - Pause the current song.

selecionarMusica(String musica) - Select a song to play.

2. Phone

Methods:

ligar(String numero) - Make a call to a specific number.

atender() - Answer an incoming call.

iniciarCorreioVoz() - Start the voicemail system.

3. Internet Browser

Methods:

exibirPagina(String url) - Display a web page.

adicionarNovaAba() - Add a new tab.

atualizarPagina() - Refresh the current page.

UML Diagram

The following UML diagram models the relationships between the classes and interfaces used in the project:

classDiagram
class ReprodutorMusical {
  + tocar()
  + pausar()
  + selecionarMusica(String musica)
}

class AparelhoTelefonico {
  + ligar(String numero)
  + atender()
  + iniciarCorreioVoz()
}

class NavegadorInternet {
  + exibirPagina(String url)
  + adicionarNovaAba()
  + atualizarPagina()
}

class iPhone {
  + tocar()
  + pausar()
  + selecionarMusica(String musica)
  + ligar(String numero)
  + atender()
  + iniciarCorreioVoz()
  + exibirPagina(String url)
  + adicionarNovaAba()
  + atualizarPagina()
}

iPhone ..|> ReprodutorMusical
iPhone ..|> AparelhoTelefonico
iPhone ..|> NavegadorInternet

How to Run

Clone the repository:

git clone https://github.com/your-username/your-repository.git

Navigate to the project directory:

cd your-repository

Compile the Java files:

javac *.java

Run the main class:

java iPhone

Example Output

Reproduzindo música...
Música pausada.
Música selecionada: Imagine - John Lennon
Ligando para: 123-456-7890
Atendendo chamada...
Iniciando correio de voz...
Exibindo página: https://www.apple.com
Nova aba adicionada.
Página atualizada.

Requirements

Java 8 or higher.

License

This project is licensed under the MIT License. See the LICENSE file for details.

Developed with ❤️ by Hian Vinicius.

