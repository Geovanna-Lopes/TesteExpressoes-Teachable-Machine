# Classificador de Expressões Faciais (Teachable Machine - Modelo de Inteligência Artificial)

## Aluna: Geovanna Lopes da Silva

Este projeto é um exercício prático da disciplina de *Tópicos Especiais e Projeto Integrador*, foi baseado na atividade proposta pelo professor Augusto Melo.
O objetivo é classificar expressões faciais utilizando um modelo treinado no Teachable Machine.

O modelo foi treinado para reconhecer as seguintes expressões:
- Sorridente
- Surpreso
- Sonolento
- Desanimado
- Chorando

# Como funciona

- O usuário acessa a aplicação web e clica no botão Iniciar.
- A aplicação solicita acesso à webcam frontal.
- A imagem da câmera é analisada continuamente pelo modelo de
inteligência artificial.
- Quando uma expressão apresenta confiança suficiente, o sistema exibe
o nome da expressão, a porcentagem de confiança e um emoji de representação da expressão correspondente.
- O botão Pausar interrompe temporariamente o reconhecimento sem desligar a câmera.
- O botão Continuar retoma o reconhecimento.

## Estrutura

index.html: interface principal e código JavaScript.

img/: imagens de emojis correspondentes às expressões reconhecidas.

model/: arquivos do modelo exportado pelo Teachable Machine.

README.md: documentação do projeto.

## Como rodar

**1. Localmente**
1. Clone este repositório.
2. Abra a pasta do projeto no VS Code.
3. Instale a extensão Live Server.
4. Abra o arquivo index.html.
5. Clique em Go Live no VS Code.
6. Acesse o endereço indicado pelo Live Server:
`http://localhost:5500/index.html`

**2.Na Web**
Acesse o projeto diretamente pelo navegador no link:
`https://github.com/Geovanna-Lopes/Teste-Teachable-Machine.git`

# Origem dos dados
Os dados foram de autoria própria, usando como exemplo várias imagens minhas fazendo expressões facias.

# Link do modelo exportado 
`https://teachablemachine.withgoogle.com/models/z2S84huuy/`

# Reflexão
Durante os testes, o modelo apresentou alguns erros de identificação, principalmente entre expressões que possuem características faciais semelhantes. Isso pode ter acontecido porque as expressões faciais envolvem diferentes músculos e pequenas mudanças no rosto podem alterar a classificação. Além disso, a iluminação, o posicionamento do rosto e a quantidade de exemplos utilizados no treinamento podem influenciar o resultado. O modelo apresentou também apresentou dificuldades de identificação quando testado em um local onde o fundo tinha muitas informações (fundo poluído). Com mais dados e exemplos variados, o modelo poderia apresentar uma classificação mais precisa.
