Ficha de RPG <br>
a ideia é criar uma aplicação em C++ de uma ficha de rpg com possibilidade de cadastrar missões e players

##

classes=> Personagens, Jogadores, Missões, Armas, Raça, Magia

Personagens
atributos->
String nome;
String classe;
int nivel;
Jogador jogador;
Armas arma;
Raça raça;
Magia magia;
String alinhamento;

##

Jogadores
atributos->
String nome;
Personagem personagem;

##

Missões
atributos->
String nomeMissao;
int nivel;
Personagens personagens;
String local;

##

Armas
atributos->
String nome;
String tipo;
int nivel;
String dano;
Magia magia;

##

Raça
atributos->
String nome;
String habilidades;

##

Magia
atributos->
String nome;
int nivel;
String dano;
