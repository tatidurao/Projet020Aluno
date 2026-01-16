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
chamando-os de block1, block2 e block3 e os adicione ao world (mundo). 
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
