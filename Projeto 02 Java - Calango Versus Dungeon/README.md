# Relatório do Exercício S02E01 - João Victor (G.R) Serra Souza 

## Índice []()
<!--TOC_BEGIN-->
- [Relatório do Exercício S02E01](#Exercício-S02E01)
<!--TOC_END-->

## Exercício-S02E01
**Calango VS Dungeon**

**1) Oque fez:**
Em minha atividade tentei moldar o exemplo do calango pra algo que eu goste, um Dungeon-Crawler, gênero de jogo de RPG muito popular na época do DOS. Minha ideia principal era já adaptar o código a partir de um pequeno projeto a parte que eu havia de feito durante a cadeira de FUP, onde testei diversos mecanismos com base na geração de números aleatórios.
Usando esses sistemas, procurei fazer algo simples, porém nos moldes dos jogos que eu tanto gosto, onde o jogador poderia atacar monstros, se curar de seus ferimentos, explorar mapas e evoluir seu personagem.

**2) Com quem fez:**
Fiz o trabalho todo sozinho, com apenas a ajuda de um colega meu que entende melhor de Java, ele me ajudou a resolver algumas dúvidas que eu tinha sobre a definição das classes e sintaxes que ainda tenho dificuldade, bem como me explicar como importar funções da biblioteca do Java, que foi de grande ajuda. Fora ele, utilizei alguns sites da internet pra entender melhor o código de geração de números aleatórios, algumas duvidas joguei no Discord, e o exemplo dado pelo professor pra usar como base.

**3) Como fez:**
Tive que escrever o código duas vezes pra conseguir implementar todas as funcionalidades que queria, no geral utilizei o Netbeans como IDE, na primeira vez que escrevi, utilizei três arquivos de classe java diferente, um para os comandos, outro para o personagem dos heróis calangos e um ultimo pra usar na geração de números aleatórios. Devido a alguns problemas na parte de importar a classe que continha o "rolador de dados", resolvi deixá-lo no arquivo dos comandos. Depois de escrever todo o código, percebi que haveria uma grande dificuldade de adicionar uma interface interativa que receba os comandos do jogador. Por isso e pra refazer o código de uma forma mais limpa, resolvi reescrevê-lo do zero, reaproveitando apenas o que achei estar melhor adaptado, o que por ventura foi uma boa parte do código.
Utilizei parte do modelo dado em sala pra realizar a conjuração de magia, o método de ataques e descanso continuou basicamente o mesmo, mas mais simplificado e de facil entendimento geral. O método de consertar a arma também foi implementado no código pra deixa-lo mais dinâmico, anteriormente, o herói precisaria explorar novas salas da masmorra para conseguir encontrar uma arma nova, tornando o jogo algo bem mais tedioso.
Me utilizei de números aleatórios para realizar os encontros com inimigos e chances do seu personagem ser emboscado/atacado enquanto descansa, pra isso precisei compreender o comando de importar, bem como implementa-lo no código de maneira simples. Por ventura, o comando usado é bem semelhante ao de Javascript, não tive muita dificuldade em me adaptar.
Após escrever todos os métodos em suas devidas formas, coloquei alguns "verificadores" no fim de cada método, esses verificadores iriam verificar se o personagem havia morrido, passado de nivel, perdido/recupero energia e iria balancear a pontuação de acordo com os maximos de cada atributo, fiz isso pra evitar que o hp atual fosse maior que o hp máximo por exemplo..
Por fim, fiz o scanner, e este me deu uma grande dor de cabeça. Ainda não consegui entender exatamente como funciona a denominação da main e suas características, tive que pesquisar e pedir ajuda no Discord pra conseguir passar de um erro, este erro ocorria porquê um de meus objetos não era estático, e a main precisava que ele fosse (pelo menos foi isso que entendi do erro). Por algumas horas quebrei a cabeça, até uma alma caridosa me dar uma luz no Discord.
Depois desse perrengue foi só alegria, consegui testar o código e fiz algumas alterações menores pra corrigir erros de cálculos, ortográficos e de pontuação.

**4) O que aprendeu e o que ainda tem dificuldade:**
Aprendi muita coisa sobre a sintaxe e algumas peculiariedades sobre as classes do Java bem como da linguagem no geral, como vim do JS, é algo completamente diferente e ainda me parece bem complexo, consegui dominar pelo menos a criação de métodos para um objeto, sua invocação e a manipulação de seus atributoo os conceits/estados, bem comos de exportação e o comando extend. Também entendi como funciona um gerador de números aleatórios no Java e alguns por menores que nem sabia que seriam problema! Também compreendi como funciona um scanner, como receber inputs do usuário e convertê-los para o uso da máquina e como funciona algumas nuânsias do Java.
Minha maior dificuldade, no geral foi entender como utilizar uma classe em um arquivo diferente, isso me deu uma baita dor de cabeça por algumas boas horas, igual as características da main e o que significava cada parte da criação das classes e funções (O public,void,static...). Mas ao todo deu pra utilizar vários do conhecimento de lógica que aprendi em FUP nesta atividade.

**5)Quanto tempo levou:**
Depois do término da aula fui direto pro Netbeans começar o trabalho, terminei o primeiro código era próximo das 22:00, porém, durante todo o processo me dei um tempo pra jantar, tomar banho e descansar. O segundo código foi reescrito na quinta-feira da mesma semana, começei o processo era próximo das 19:00. Reescrever o código não foi problema, mas as características da main me travaram por um bom tempo. A resposta só foi me dada ás 22:00.Ao total, creio que levou umas 3 horas de processo até o fim do primeiro código e mais 3 pra encerrar o segundo.