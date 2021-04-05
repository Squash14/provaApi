# Prova Técnica de API

## Objetivo

O objetivo desta prova técnica é **mostrar suas habilidades em testes para API** e qual a **sua abordagem** para garantir testar a aplicação. Nós gostamos de novas idéias além das que estão nos requisitos, logo sinta-se a vontade para melhorar, adicionar ou extender.

Avaliaremos a prova técnica dependendo do seu nível de senioridade avaliando:

* cobertura de testes
* estratégia
* práticas adotadas

## O desafio

O Sicredi é uma instituição financeira cooperativa de crédito, logo disponibiliza crédito para seus associados.

Um experimento será feito para liberar uma versão de simulação de crédito. Infelizmente nós (Sicredi) não aceitamos simulações de quem tem o CPF com alguma restrição. Aqueles que não possuem restrição podem efetuar a simulação.

Como a página está em construção a API (backend) foi disponibilizada para você testar. Possuindo os seguintes funcionalidades:

* consultar restrição por um CPF
* cadastrar uma simulação
* consultar todas as simulações cadastradas
* consultar uma simulação pelo CPF
* alterar uma simulação
* remover uma simulação

Sua tarefa é criar um projeto de teste para automatizar as funcionalidades do projeto de API REST.

Ela deve ser desenvolvida totalmente em código na linguagem de programação que você escolher com a ajuda de algum framework/biblioteca com esta capacidade. Você não deve usar ferramentas de record-and-play (gravar e executar) utilizando ferramentas como Postman ou Katalon, ou qualquer framework/ferramnenta que gera o código para você.

## Sobre o projeto

Toda documentação da API (Swagger) bem como as regras de negócio e como executar a aplicação estão no _README_ do projeto.

## Obrigatório a fazer

* cobertura funcional dos cenários, incluindo fluxos de exceção
* documentação como codigo, ou seja, os scripts devem ser os mais claros possíveis
* um _README_ contendo:
  * como executar os testes (assuma que nós não conhecemos a linguagem de programação que você utilizar)

A aplicação deve executar localmente, independente do sistema operacional utilizado, apenas sendo necessário o projeto de API executando.

## O que é legal ter

Se você cumpriu os requisitos _Obrigatórios a fazer_ temos algumas recomendações do que fazer a mais, se você tiver tempo:

* relatório, gerado de forma automática, com os resultados dos testes
* qualquer bug encontrado deve ser reportado no repositório com informações relevantes para a sua reprodução
* documentação de um plano de teste e estratégia de testes (quais os testes foram deixados para trás e porquê)
  * você pode escolher o formato da documentação, mas ela deve estar no repositório
* sugestões de melhoria
* uso da linguagem de programação Java

## Entrega

Por favor entregue o link para o repositório do desafio no seu GitHub/GitLab/Bitbucket pessoal até o prazo de entrega
informado a você.
