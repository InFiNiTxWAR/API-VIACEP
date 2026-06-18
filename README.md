# Consulta ViaCEP

## Descrição

Este projeto é uma aplicação web desenvolvida em HTML, CSS, JavaScript e Bootstrap que permite consultar endereços utilizando a API ViaCEP.

O sistema oferece duas formas de pesquisa:

* Consulta por CEP.
* Consulta por Rua, Cidade e UF.

Os dados retornados pela API são exibidos de forma organizada em cartões modernos e responsivos.

---

## Tecnologias Utilizadas

* HTML5
* CSS3
* JavaScript
* Bootstrap 5
* API ViaCEP

---

## Funcionalidades

### Consulta por CEP

O usuário informa um CEP e o sistema retorna:

* Logradouro
* Bairro
* Cidade
* UF
* Estado
* Região
* DDD
* Código IBGE

### Consulta por Rua

O usuário informa:

* UF
* Cidade
* Rua

O sistema retorna todos os endereços encontrados com as informações correspondentes.

### Tratamento de Erros

O projeto exibe mensagens amigáveis quando:

* O CEP não é encontrado.
* A rua não é encontrada.
* Ocorre erro na comunicação com a API.

---

## Interface

O projeto possui uma interface moderna utilizando:

* Fundo com gradiente escuro.
* Barra de navegação estilizada.
* Campos de formulário arredondados.
* Cartões com sombras e animações.
* Efeitos visuais ao passar o mouse sobre botões e resultados.

---

## API Utilizada

ViaCEP

Endpoint para consulta por CEP:

https://viacep.com.br/ws/CEP/json/

Exemplo:

https://viacep.com.br/ws/01001000/json/

Endpoint para consulta por endereço:

https://viacep.com.br/ws/UF/CIDADE/RUA/json/

Exemplo:

https://viacep.com.br/ws/SP/Sao%20Paulo/Avenida%20Paulista/json/

---

## Como Executar

1. Faça o download dos arquivos do projeto.
2. Abra o arquivo `index.html` em um navegador.
3. Escolha o tipo de consulta.
4. Informe os dados solicitados.
5. Clique em "Consultar".

---

## Objetivo

Este projeto foi desenvolvido com o objetivo de praticar:

* Consumo de APIs REST.
* Programação assíncrona com Fetch API.
* Manipulação do DOM.
* Desenvolvimento de interfaces responsivas.
* Integração entre HTML, CSS e JavaScript.
