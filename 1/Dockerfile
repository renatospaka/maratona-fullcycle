# instala a imagem do GO v1.14
FROM golang:1.14

# copia a raiz do projeto para a raiz do contêiner
COPY . .

# compila o arquivo e gera o executável..
RUN go build main.go

EXPOSE 8080

# executa o arquivo main.exe
ENTRYPOINT ["./main"]