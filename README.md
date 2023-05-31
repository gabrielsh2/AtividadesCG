# Computação Gráfica - Gabriel Hoffmann

## M1

Adicionado os Projetos:

- Hello3D
- Hello3D - withShaderClass
- HelloTextures

Seguindo como base o exemplo passado na tarefa e fazendo as alterações solicitadas.

## M2

Adicionado o projeto M2 - Cubo.

Esse projeto foi criado com base na pirâmide e primeiramente foi alterado o vetor de vértices e a função de desenhar triângulos para representar um cubo.

Após isso foram criadas funcionalidades de escala usando o glm::scale e de translação utilizando o glm:translate. Permitindo alterar aumentar e diminuir a escala do cubo e move-lo a partir do teclado.

Por último foi criada mais uma instância de cubo alterando o vertexShader, atualizado a função de desenho para uma função com instâncias e alterado o método setupGeometry para utilizar um segundo VBO que controle as instâncias.

## M2 - Vivencial

Adicionado o projeto M2 Vivencial - Suzanne

Utilizando o OBJ disponibilizado pela professora no git e o projeto M2 - Cubo como base foi feito a leitura do OBJ Suzanne e mostrado em tela.

Para isso busquei tutoriais para ler um OBJ e armazenar seus vértices em um vetor. Substituindo dessa forma o array de vértices que representavam o cubo e suas cores.

Além disso também foi mudado as chamadas das funções de desenho no loop para representar a Suzanne da mesma forma que está no gif da professora no teams.
