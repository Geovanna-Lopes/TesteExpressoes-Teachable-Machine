# Classificador de Expressões Faciais (Desafio 01 - Teachable Machine)

## Aluna: Geovanna Lopes da Silva

Este projeto é um exercício prático da disciplina de *Tópicos Especiaas e Projeto Integrador*, foi baseado na atividade proposta pelo professor Augusto Melo.
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

/
├── index.html
├── README.md
├── model/
│   ├── model.json
│   ├── metadata.json
│   └── model.weights.bin
└── img/
    ├── sorridente.png
    ├── surpreso.png
    ├── sonolento.png
    ├── desanimado.png
    └── chorando.png

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
Acesse o projeto diretamnet pelo navegador no link:


# Origem dos dados
Os dados foram de autoria propria, usando como exemplo várias imagens minhas fazendo expressões facias.

# Link do modelo exportado 
`https://teachablemachine.withgoogle.com/models/z2S84huuy/`

# Reflexão
No início cometeu alguns erros em relação a uma leve confusão de má identificação, pois as expressões facias mexem com musculos.....