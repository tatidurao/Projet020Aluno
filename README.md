Tarefas específicas para completar o projeto:
1. Ajuste o tamanho da tela e mude a cor de fundo (background).
2. Chame update() para atualizar o motor de física em draw().
  Dica: Engine.update(engine)

3. Crie um corpo plano que será o solo do jogo.
  ● Adicione um corpo plane (plano) ao mundo.
  ● A propriedade isStatic de plane será true (verdadeira).
    Dica: var plane_options = {
             isStatic = True
           }
4. Crie três corpos com formas diferentes, como quadrado, círculo e retângulo,
chamando-os de block1, block2 e block3 e os adicione ao world (mundo). Ver dica 1
  ● Chame fill(), rectMode() e ellipseMode() para estilizar os corpos.
🟥, 🔴, ▆

5. Adicione diferentes propriedades físicas. (Veja Dica 2)
  ● Defina restitution, friction e frictionAir para os corpos.
  ● Certifique-se de adicionar valores diferentes para corpos diferentes.
6. Agora crie uma forma para todos os corpos usando ellipse() e rect() dentro da função
draw().
7. Você deverá ser capaz de ver a diferença no comportamento dos objetos depois que a
física é aplicada a eles.
8. Certifique-se de que o projeto está funcionando antes de enviá-lo.

Dicas 1 e 2:

block1 = Bodies.circle(220, 10, 10, block1_options);
World.add(world, block1);

block2 = Bodies.rectangle(110, 50, 10, 10, block2_options);
World.add(world, block2);

block3 = Bodies.rectangle(350, 50, 10, 10, block3_options);
World.add(world, block3);



var block1_options = {
  restitution: 0.5,
  friction: 0.02,
  frictionAir: 0
}
var block2_options = {
  restitution: 0.7,
  friction: 0.01,
  frictionAir: 0.1
}
var block3_options = {
  restitution: 0.01,
  friction: 1,
  frictionAir: 0.3
}

