# projetoDio-diagrama-de-classe
Criado um diagrama de classe tendo como exemplo o lançamento do Iphone 17, seguindo o objetivo do desafio do curso de Orientação ao objeto. 


classDiagram
    class ReprodutorMusical {
        +tocar() void
        +pausar() void
        +selecionarMusica(musica: String) void
    }

    class AparelhoTelefonico {
        +ligar(numero: String) void
        +atender() void
        +iniciarCorreioVoz() void
    }

    class NavegadorInternet {
        +exibirPagina(url: String) void
        +adicionarNovaAba() void
        +atualizarPagina() void
    }

    class iPhone {
        +tocar() void
        +pausar() void
        +selecionarMusica(musica: String) void
        +ligar(numero: String) void
        +atender() void
        +iniciarCorreioVoz() void
        +exibirPagina(url: String) void
        +adicionarNovaAba() void
        +atualizarPagina() void
    }

    ReprodutorMusical <|.. iPhone
    AparelhoTelefonico <|.. iPhone
    NavegadorInternet <|.. iPhone

  
