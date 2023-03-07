# meusprojetos
Repositório para incluir os fontes e demais arquivos referente a aulas, cursos, treinamentos, testes

Desafio Full Cycle 3.0#
Criar uma aplicação em GO que demonstre "Full Cycle Rocks!", deve ter um tamanho < 2 Mb.

Para baixar a imagem:

docker push jeancalao/fullcycle:latest

os programas desenvolvido em GO estão no repositório:

Para compilar com um tamanho reduzido utilizei o comando

go build -ldflags "-s -w" fullcycle.go

Ao executar o docker run, aparece como resultado da imagem:

![image](https://user-images.githubusercontent.com/127217371/223456819-dd951cf7-b926-448e-aa36-27d176132058.png)

Conforme podemos ver, a imagem ficou com um tamanho < 2 MB:

![image](https://user-images.githubusercontent.com/127217371/223457388-5718af53-6f86-4dab-9cf4-4d7bbcc6d05a.png)

