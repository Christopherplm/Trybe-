#1 - Configurar Ubuntu - ok 
#2 - Instalar node - ok 
#3 - Copiar o script para o container -
#4 - Executar com Node  


FROM ubuntu:20.04

RUN apt-get update && apt-get install nodejs -y 

WORKDIR /app

COPY aula.js . 

CMD [ "node", "aula.js"]