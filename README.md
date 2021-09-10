Lista de exercícios 2 - Ciência da Computação 2021/2 - Luiz Gonzaga da Silveira Junior

Aluna: Nadine Schneider

Exercício 1:

--- Alteração ---
Alterado método void processInput(GLFWwindow *window) do arquivo List2-Exer1 para adicionar o controle do percentual do mix. 
O controle ocorre através da variável uniformMix.
Essa mesma variável de controle foi adicionada também no arquivo 4.2.texture.fs.

--- Orientações de uso ---
Rodar o projeto.
Usar as setas da esquerda e direita para simular o mix das texturas. 

Exercício 2:

--- Alteração ---
Alterada propriedade dos materiais no laço while (!glfwWindowShouldClose(window)).
Os valores de X,Y,Z utilizados foram do material CYAN RUBBER.

--- Orientações de uso ---
Rodar o projeto apenas e já é possível visualizar o resultado.  

Exercício 3:

--- Alteração ---
Alterado o arquivo 4.2.lighting_maps.fs, modificando os cálculo das variáveis ambient, diffuse e specular. 

--- Orientações de uso ---
Rodar o projeto apenas e já é possível visualizar o resultado.  

Exercício 4:

--- Alteração ---
Adicionadas variáveis de specularMap e emissionMap no arquivo List2-Exer4. 
Depois foi feito o bind dessas novas variáveis dentro do laço while (!glfwWindowShouldClose(window)).
Adicionado também no arquivo 4.1.lighting_maps.fs os sampler2D specular e emission.

--- Orientações de uso ---
Rodar o projeto apenas e já é possível visualizar o resultado.  
