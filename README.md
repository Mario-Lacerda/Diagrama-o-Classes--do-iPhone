# Orientação a Objetos e UML: Diagramação de Classes do iPhone

Aqui se encontra minha implementação do [Desafio de projeto](https://github.com/digitalinnovationone/trilha-java-basico/tree/main/desafios/poo) da [DIO](https://www.dio.me/bootcamp/coding-future-gft-aws-desenvolvimento-java-com-cloud-aws)

Com base no vídeo de lançamento do iPhone conforme link abaixo, elabore em uma ferramenta de UML de sua preferência. A diagramação das classes e interfaces com a proposta de representar os papéis do iPhone de: Reprodutor Musical, Aparelho Telefônico e Navegador na Internet. Em seguida crie as classes e interfaces no formato de arquivos .java

[Lançamento iPhone 2017](https://www.youtube.com/watch?v=9ou608QQRq8)



Este é um diagrama UML que representa a estrutura de classes e interfaces para um sistema que inclui a modelagem do iPhone, um dispositivo que incorpora funcionalidades de um reprodutor de música, um telefone e um navegador de internet. Este diagrama foi criado como parte do desafio de projeto Formação Java Developer na DIO.me.

![iphone](assets/iphone.png)


## Descrição das Interfaces e Classes

### Reprodutor Musical (ReprodutorMusical)

A interface `Reprodutor Musical` é responsável por implementar a funcionalidade de reprodução de arquivos de áudio. Ela possui métodos como `tocar()`, `pausar()`, e `selecionarMusica()`. A classe `Musica` armazena informações sobre as músicas.

### Aparelho Telefônico (AparelhoTelefonico)

A interface `Aparelho Telefônico` é responsável por implementar a funcionalidade de um telefone. Ela possui métodos como `ligar()`, `atender()`, e `iniciarCorreioVoz()`. A classe `Contato` armazena informações de contatos.

### Navegador de Internet (NavegadorInternet)

A interface `Navegador de Internet` é responsável por implementar a funcionalidade de um navegador web. Ela possui métodos como `exibirPagina()`, `adicionarNovaAba()`, e `atualizarPagina()`.
