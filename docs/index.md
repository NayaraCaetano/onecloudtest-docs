#Introdução
-------------
Documentação dos processos executados para realização do desafio técnico QA.

> **Contatos:**

>  - **Nome**: Nayara Caetano Pinheiro
>  - **Email**: nayara.caetanopinheiro@gmail.com
>  - **Telefone**: (38) 99118-9910



#Testes
-------------
Documentara os testes.

##Teste caixa branca

Testa as regras de negócio da aplicação.

Repositório (fica dentro da aplicação): [https://github.com/NayaraCaetano/onecloud-qa](https://github.com/NayaraCaetano/onecloud-qa)

**Motivações:**

  - Execução mais rápida que testes caixa preta;
  - Pode ser mais facilmente executado pelo próprio *dev* em refatorações de código, por exemplo;


**Ferramentas adicionais envolvidas:**

  - [Pytest](http://pytest.org/latest/);
  - [FactoryBoy](https://factoryboy.readthedocs.io/en/latest/): para facilitar a criação da base de dados para teste executar;
  - [Coverage](https://coverage.readthedocs.io/en/coverage-4.1/): para medir a cobertura dos testes;


**Observações:**

  - Criei a app `core` para exemplificar a forma com que gosto de estruturar o código, pelo tamanho da aplicação do teste ela não seria tão necessária;
  - Não nomear as urls (para utilização da função `reverse` do `django.core.urlresolvers`) não é uma boa prática. Caso um endereço mude, todas as chamadas à url *hard coded* precisariam ser alteradas.



#Observações gerais
-------------
  - Eu, de certa forma, inferi algumas regras de negócio da aplicação, numa situação real eu teria estas informações.


#Outras Ferramentas
-------------
- [Joe](https://github.com/karan/joe): Gerador "mágico" de arquivos .gitignore;