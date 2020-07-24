## Rodando o projeto

Este projeto pode rodar tanto em ambiente de desenvolvimento ou em modo de produção em um container docker.

Para iniciar o projeto em desenvolvimento:
- Tenha o NodeJs instalado
- Clone este repositório para a sua máquina local
- Entre com o comando `yarn` ou `npm install`, dependendo do seu gerenciador de pacotes
- depois de instalados os pacotes da aplicação, inicie com `yarn start` ou `npm start`
- A aplicação estará disponível no endereço http://localhost:3000.

Para iniciar o projeto em um container Docker:
- Certifique de possuir Docker instalado na sua máquina
- Para gerar a imagem entre com o comando `docker build -t hurb-charlie .`
- Aguarde o processo todo finalizar
- Depois com a imagem criada entre com o comando `docker run -p 5000:5000 --name {nome do container} -d hurb-charlie`.
- Com isto a aplicação estará disponível no endereço http://localhost:5000

