Descrição
=================
Alguns macros úteis para o Roll20 desenvolvidos para agilizar o jogo, diminuir o espaço gasto no chat para rolagem de dados e padronizar as ações dos personagens.

A lista dos macros inclusos no Macros_roll20.txt podem ser vistos na [lista de macros](#lista-de-macros) no final do README

Guia para iniciantes
=================

Os macros estão sempre indicados por **###Nome do macro**, deve-se copiar o conteúdo todo abaixo desse marcador até o final (espaço anterior ao macro seguinte), como por exemplo:

![iniciante](images/iniciante.png)

A maioria dos macros foi desenvolvida pensando que os jogadores iriam adicionar os macros relativos à ficha da seguinte forma:

Primeiro, abrir a ficha do personagem:

![img1](images/img1.png)

Selecionar a aba 'Attributes & Abilities' e em seguida clicar em '+Add':

![img](images/img2.png)

Copiar o conteúdo do macro que deseja e colar da seguinte forma:

![img3](images/img3.png)

Ao salvar o macro (pressionar o botão 'v'), selecionar 'Show in Macro Bar' e ter-se-á uma tela parecida com:

![img4](images/img4.png)

Inicialmente o nome do macro será da forma *charname : habilidade*, para alterar cor e nome basta clicar com o botão direito nesse botão.

> Tenha em mente que os macros abaixo do marcador 'GERAIS' (no arquivo *.txt) não precisam ser editados, porém os que antecedem esse marcador, foram criados especificamente para personagens, assim para serem utilizados por outros personagens, é necessário editar os pedaços que contenham @{Zikko Bruhnog | atr}, por exemplo, para @{nome do seu personagem | atr}


Exemplos de alguns macros
=================
### Perícias

A caixa seletora funciona basicamente da mesma forma para o macro de *Atributos*

![img6](images/img6.png)

![img5](images/img5.png)

No chat aparecerá da seguinte forma:

![img7](images/img7.png)

### Imagem

![](images/img8.png)

No chat:

![](images/img9.png)

### Texto

![img10](images/img10.png)

No chat:

![](images/img11.png)

### XdY+bonus

O macro de d20+bonus funciona de forma similar

![](images/img12.png)

![](images/img13.png)

![](images/img14.png)

No chat:

![](images/img15.png)

### Pedágio aos Mortos

![](images/img16.png)

No chat:

![](images/img17.png)

Lista de Macros
=================
#### Uso Geral
- Atributos: para rolagem de testes de atributo com seletor para vantagem, desvantagem ou teste normal
- Perícias: para rolagem de perícias com seletor para vantagem, desvantagem ou teste normal
- d20+bonus: para agilizar rolagens de d20 com bônus quaisquer
- XdY+bonus: para facilitar a rolagem de uma quantidade qualquer de dados com número arbitrário de dados com bonus
- Imagem: para otimizar o envio de imagens pelo chat
- Texto: para enviar um texto no chat com formato diferente

#### Para jogadores

+ Pedágio aos mortos (toll the dead): adicionar a magia no roll20, que não está presente na versão grátis, possibilita a rolagem se o inimigo levou dano ou não (1d8 ou 1d12) e rola o número de dados de dano permitidos para cada nível, além de mostrar a CD do teste de resistência, tipo de dano e alcance
+ Mordida do Adran: macro desenvolvido para que o personagem Vampiro da campanha pudesse realizar sua fatídica mordida: 1d20 + modificador de força + bônus de proficiência, dando 1d6 + modificador de força de dano necrótico