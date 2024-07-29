# Primeiro_Jogo_Unity_2D  
  Jogo desenvolvido numa capacitação dos cursos da Tomorrow na UFBA. Trata-se de um curso de Desenvolvimento de Jogos com Unity para Plataformas Móveis. Onde aprendi não só como usar a Unity, como criar um jogo 2D, além de explorar C# com os scripts de elementos do jogo.  
  
<div align="center">
    <img width="50%" title="Capa do curso Tomorrow UFBA" src="https://tomorrow.ufba.br/sites/tomorrow.ufba.br/files/5.png"/>
<div>

## Atividade 1
  Durante a atividade 1, desenvolvi as ligações dos estados Poisoned, InjuredPoisoned e o PlayerShowOff e atribuí um botão específico para cada um deles. Shift+Esq para poisoned, shift+dir para injuredpoisoned e o pageup seria o showoff, além do injured que foi atribuído a tecla backspace. Ao longo do projeto, algumas foram usadas como condição para determinada função, outras não tiveram importância devido a independência de determinado estado.  
	Para isso, no Script:  
 
<div align="center">
    <img width="80%" title="1º Fragmento de código da atividade 1" src="https://github.com/user-attachments/assets/bf99154d-dda0-4545-a608-8e07ca090ea2"/>
<div>

<br>

<div align="center">
    <img width="80%" title="2º Fragmento de código da atividade 1" src="https://github.com/user-attachments/assets/502fda83-370f-449d-8640-4beddde4c11b"/>
<div>

<br>

<div align="center">
    <img width="80%" title="3º Fragmento de código da atividade 1" src="https://github.com/user-attachments/assets/e7a1f377-3a76-43a5-9ee8-bcace83939f5"/>
<div>

<br>

## Atividade 2
  Durante a atividade 2, desenvolvi funções que permitem o zoom in e zoom out da câmera que segue o player (personagem principal do jogo) com o gesto de pinça na tela pelo celular. Além disso, um duplo toque deve recuperar o zoom padrão da câmera.  
  Para isso, no script:  

<div align="center">
    <img width="80%" title="Fragmento de código da atividade 2" src="https://github.com/user-attachments/assets/8df69e0a-14f2-4cc5-a482-13aae9834838"/>
<div>

  Temos uma condição que verifica o duplo toque e através da diferença de distância entre os dedos, ajustamos o zoom da câmera, respeitando os limites de Zoom que já estava definido como mínimo e máximo.

<br>

<div align="center">
    <img width="80%" title="Fragmento de código da atividade 2" src="https://github.com/user-attachments/assets/e03ab3fa-847f-49ca-bdda-184723b9bbb3"/>
<div>

  Caso a condição do toque duplo fosse falsa, verificamos o toque único. Se forem dois cliques na tela de toque único, definimos o zoom da câmera para o zoom padrão.  

<br>

  Testando cada função, em ordem: Pinça depois o clique duplo:

<div align="center">
    <img width="80%" title="GIF mostrando funcionalidade do zoom da atividade 2" src="https://github.com/user-attachments/assets/f5dc2971-227f-475c-b6f4-e3252dd7559d"/>
<div>

<br>

  ## Atividade 3
  Durante a atividade 3, desenvolvi uma série de funções, estados, elementos estudados desde o início da capacitação para conseguir finalizar o projeto com um cenário de fundo de jogo com paletas e regras aprendidas em aulas anteriores.  
  Além disso, implementei inimigos que se movem ao redor do cenário usando a técnica do raycasting para encontrar limites de distância até uma parede ou buraco no cenário.  

<div align="center">
    <img width="80%" title="GIF mostrando funcionalidade do zoom da atividade 2" src="https://github.com/user-attachments/assets/8e385ae3-47d1-4341-a926-74ade2cb7430"/>
<div>
  
  Prévia do mapa criado. Paletas diferentes, áreas novas, inimigos tanto fixos como móveis por todo o mapa.  

<br>

  ## Desafio
  Aproveite para jogar um pouco. Desafio você a fazer uma speedrun abaixo de 3 min e meio até a cena de vitória do jogo sem tomar dano. Dica: Ouro!  

<div align="center">
    <img width="80%" title="OURO! Consegue fazer a speedrun?" src="https://github.com/user-attachments/assets/8f488983-a172-4a27-a134-a651d8e23273"/>
<div>

<br>

  ## Créditos
  Deixo o reconhecimento da arte do jogo (por sinal, muito bem feita!) para Crusenho. Segue perfil e o assets do jogo desse artista:  
  ### Perfil do artista na Itch.io:  
  https://crusenho.itch.io/  
  ### Assets do jogo:  
  https://crusenho.itch.io/beriesadventureseaside/  

OBS.: Infelizmente, são muitos arquivos do jogo. Não consigo anexá-los aqui, mas deixei um executável para instalar e jogar! 📲 🎮
