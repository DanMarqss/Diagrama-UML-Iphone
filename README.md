# Diagrama-UML-Iphone
Desafio de Criação de Diagrama UML

# [DIO](www.dio.me) - Trilha Java Básico

## Autores
- [Danilo Marques](https://github.com/DanMarqss)

## POO - Desafio

### Modelagem e Diagramação de um Componente iPhone

Neste desafio, sou responsável por modelar e diagramar a representação UML do componente iPhone, abrangendo suas funcionalidades como Reprodutor Musical, Aparelho Telefônico e Navegador na Internet.

#### Contexto
Com base no vídeo de lançamento do iPhone de 2007 (link abaixo), eu elaborei a diagramação das classes e interfaces utilizando uma ferramenta UML de sua preferência. Em seguida, implemente as classes e interfaces no formato de arquivos `.java`.

[Lançamento iPhone 2007](https://www.youtube.com/watch?v=9ou608QQRq8)
- Minutos relevantes: 00:15 até 00:55

#### Funcionalidades a Modelar
1. **Reprodutor Musical**
   - Métodos: `tocar()`, `pausar()`, `selecionarMusica(String musica)`
2. **Aparelho Telefônico**
   - Métodos: `ligar(String numero)`, `atender()`, `iniciarCorreioVoz()`
3. **Navegador na Internet**
   - Métodos: `exibirPagina(String url)`, `adicionarNovaAba()`, `atualizarPagina()`

### Objetivo
1. Criar um diagrama UML que represente as funcionalidades descritas acima.
2. Implementar as classes e interfaces correspondentes em Java (Opcional).

### Diagrama UML (Mermaid)
```mermaid
classDiagram
    class iPhone {
    }

    class MusicPlayer {
        +void tocar()
        +void pausar()
        +void selecionarMusica(String musica)
    }

    class PhoneDevice {
        +void ligar(String numero)
        +void atender()
        +void iniciarCorreioVoz()
    }

    class InternetBrowser {
        +void exibirPagina(String url)
        +void adicionarNovaAba()
        +void atualizarPagina()
    }

    iPhone --|> MusicPlayer
    iPhone --|> PhoneDevice
    iPhone --|> InternetBrowser

```

### Instruções
1. Assisti ao vídeo do lançamento do iPhone para entender as funcionalidades principais.
2. Utilizez uma ferramenta UML de sua preferência para criar o diagrama das classes e interfaces. Você pode utilizar o modelo acima (criado na sintaxe [Mermaid](https://mermaid.js.org/)), uma alternativa open-source e compatível com arquivos Markdown como este.
4. Submeti meu repositório GitHub conforme as orientações da plataforma DIO. Por exemplo:

```bash
https://github.com/glysns/trilha-java-basico/desafios/poo/README.md
```` 
