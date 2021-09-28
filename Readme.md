## Jogo Chapéuzinho Vermelho

O intuito deste programa é recriar um pequeno jogo de turno, utilizando alguns personagens da história da Chapéuzinho Vermelho. O projeto foi criado para um trabalho da faculdade, do curso de Ciência da Computação.

### Corpo do projeto

O programa consiste em um pacote Principal, onde está localizado uma classe que gerenciará os comandos do jogo, como por exemplo dano, tempo de turno, escolha de caminho para seguir, etc, e um pacote Modelo, onde está as classes contendo os personagens da história. Assim, o jogo se baseia em cada vez que um personagem é derrotado, você escolhe um caminho para seguir, e outro personagem aparece para você derrotar.

### Personagens

* Cada personagem tem um set de habilidades, ao qual cada habilidade tem uma quantidade de dano, custo de mana para ser usado e tipo de dano (magia ou ataque);
* Cada vez que o personagem usa uma habilidade um texto indicando a ação é mostrado;
* Quando a Chapéuzinho derrota um personagem, ela ganha uma quantidade de experiência, e assim, caso ela alcance uma determinada experiência quantidade de experiência, ela conseguirá subir 1 nivel;
* A cada nível alcançado um atributo pode ser escolhido para melhorar, dentre vida, ataque e mana;

### Objetivo 

O objetivo do jogo é chegar até a casa da vovó, e a cada monstro derrotado a porcentagem para a chegada aumenta, assim chegando ao fim do jogo.
