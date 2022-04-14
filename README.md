# TDD_alugarCarro_projeto_curso

Projeto construído durante o módulo de testes do treinamento Javascript Expert que estou cursando atualmente, do professor Erick Wendel.

Esse projeto tem como objetivo aprender os conceitos e executar na prática o método de desenvolvimento TDD (Test Driven Development), também de testes unitários, testes ponta a ponta, e cobertura de código na prática .

Dado o caso de uso criamos os testes, após as falhas, fizemos a implementação e melhoria, por fim adicionamos uma camada de rotas para apresentação.

Conceitos abordados:

-Testes
-TDD
-Mocks e stubs
-Cobertura de código
-seeds
-testes end-to-end
-code coverage

Tecnologias:

-Javascript
-Node
-Mocha (Framework, motor de testes)
-Sinon (Framework)
-NYC (Biblioteca para cobertura de código)
-Supertest (Framework)

Executando o projeto:

Em uma pasta faça um git clone na url deste diretório.
Rodar o comando 'npm run seed' para que o nosso banco de dados fictício seja populado (arquivos JSON).
A aplicção pode ser rodada com o comando 'npm run start'.
'npm run test' para verificar os testes escritos.
'npm run test:cov' para o IstanbulJS verificar a cobertura do código.
Rotas:

POST: /rent
POST /calculateFinalPrice
POST /getAvailableCar
