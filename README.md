## Building Conversao-Distancia

#### Sobre a Aplicação

### Obtida por meio de fork do projeto do Desenvolvedor Fabricio Veronez
### URL do Projeto no GitHub ==> https://github.com/KubeDev/conversao-distancia

- Aplicação usada para converter a distancia em "Metro" para "Quilômetros" e vice-versa através de um frontend simples.
- Porta de execução: 5000
- Escrita em Python / Flask.

## Docker

Caso queira não queira usar o Dockerfile oferecido nesse repositório você pode clonar o projeto e fazer seus próprios ajustes no Dockerfile e gerar sua imagem local.

$ ```git clone https://github.com/ricellirousselet/conversao-distancia.git```

$ ```docker build -t <image-name> .```

#### Usando a aplicação "conversao-distancia"

## Versão Latest (1)

$ ```docker run -d -p 5000:5000 --name conversao-distancia ricellirousselet/conversao-distancia```

## Versão 1

$ ```docker run -d -p 5000:5000 --name conversao-distancia ricellirousselet/conversao-distancia:1``` 

## Acessando container "conversao-distancia"

$ ```docker container exec -it conversao-distancia /bin/sh```
