# meusprojetos
Repositório para incluir os fontes e demais arquivos referente a aulas, cursos, treinamentos, testes

Desafio Full Cycle 3.0#
Criar uma aplicação em GO que demonstre "Full Cycle Rocks!", deve ter um tamanho < 2 Mb.

Para baixar a imagem:

docker push jeancalao/fullcycle:latest

os programas desenvolvido em GO estão no repositório:

Para compilar com um tamanho reduzido utilizei o comando

go build -ldflags "-s -w" fullcycle.go
