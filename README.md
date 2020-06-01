# Design Patterns - Mediator

O Mediator faz parte do grupo de padrões comportamentais, tendo como objetivo encapsular a forma que objetos interagem.

Ele faz isso criando um objeto *mediator* que irá cuidar da comunicação de todos os objetos associados.

Imagine em um aeroporto, a torre de controle seria uma analogia ao mediador, pois ela dita quem pode aterrisar, quem pode decolar.
Se a torre não existisse, os aviões teriam de comunicar entre si para organizar as decolagens e aterrisagens.

Utilize o mediator quando:
* For díficil de fazer uma alteração em uma classe pois elas são **fortemente** acopladas
* Quando você não puder reutilizar um componente em um programa diferente pois ele é muito dependente de outros componentes
* Quando você se encontrar criando diversos componentes somente para utilizar um comportamento basico em diferentes contextos.
