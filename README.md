# AtividadeCena
Cauã Magalhães e Gustavo Henrique

# Link para o drive

https://drive.google.com/file/d/1MVlsc42ZZATcAwbOPxDe2zNz_yRgz8G8/view?usp=sharing

# Descrição

Está e uma cena no Unity 3d, onde o objetivo é passar de um labirinto, e encontrar o final para uma recompensa.

# Cena

Para a criação desta cena, foram utilizados GameObjects , assests gratuitos da Unity store, Objetos e personagem modelados no blender.

# GameObjects

<h1>Feitos no blender.</h1>

Sapos.<br>
<img src="img/Sapos.png" width = "200" height = "200">
<img src="img/Mulher-sapo.png" width = "200" height = "200">  

Labirinto.<br>
<img src="img/Labirinto.png" width = "200" height = "200"> 

Textos.<br>
<img src="img/Texto-1.png" width = "300" height = "200">
<img src="img/Texto-2.png" width = "200" height = "200">  
<br>

<h1>Assets</h1>

Natureza.<br>
<img src="img/Natureza.png" width = "200" height = "200">

Báus.<br>
<img src="img/Bau-Secreto.png" width = "200" height = "200">
<img src="img/Bau-fim.png" width = "200" height = "200">
<br>

<h1>Feitos no Unity</h1>
Luzes utilizadas: Directional Light, e 2 Point Lights para os Báus.<br>
Camera, para seguir o personagem.<br>
Materiais.<br>
<img src="img/Materiais.png" width = "400" height = "100">

Coração: foram utilizados dois 3D Objects de "Capsule"<br>
<img src="img/Coracao.png" width = "200" height = "200">

Paredes do fim, e chão foram feitos com cubos
<br>

# Script

<h1>Movimento</h1><br>
<img src="img/Player.png" width = "200" height = "200">

Este código é para movimentar o personagem, no caso o "Sapo". Ele permite que o personagem se mova pelas teclas do teclado (W, A, S, D). A função "transform.Translate" é usada para realizar o movimento do personagem no espaço. A linha "print(isLeftButtonDown)" imprime no console se o botão esquerdo do mouse está sendo pressionado ou não.

<h1>Rotação</h1><br>
<img src="img/Rotacao-1.png" width = "200" height = "200">
<img src="img/Rotacao-1.png" width = "200" height = "200">

Este código controla a rotação do personagem usando o movimento do mouse. Dependendo do valor da variável "axes", ele rotaciona o objeto nos eixos X e Y. Os valores de movimento do mouse são obtidos com "Input.GetAxis" e a rotação é aplicada usando as funções "transform.Rotate" e "transform.localEulerAngles".
