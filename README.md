# Conversor de Moedas One
✅ Descrição:

Este é um Conversor de Moedas desenvolvido como Chalenger do ONE.
Trata-se de uma aplicação Java 21 com Spring Boot, executada totalmente no terminal, que permite converter valores entre moedas latino-americanas usando taxas reais via ExchangeRate-API — com fallback automático para taxas locais em caso de falha.

⚙️ Funcionalidades

✅ Conversão entre USD, BRL, ARS, BOB, CLP, COP

✅ Consulta de taxas em tempo real (com cache inteligente)

✅ Backup automático de taxas offline

✅ Interface amigável e colorida no terminal

✅ Suporte a .env para configuração de chave de API

✅ Totalmente desenvolvido com boas práticas Java (Java 21, Lombok, Maven)

🚀 Como Executar:

1 - git clone https://github.com/seu-usuario/conversor_one.git

cd conversor_one

2 - Configure sua chave da API:

Crie um arquivo .env na raiz do projeto:
API_KEY=sua_chave_da_exchangerate_api

3 - Compile e execute com Maven:

mvn clean install
mvn spring-boot:run

Exemplo de Uso:

=======================================
CONVERSOR DE MOEDAS 
=======================================
Escolha uma opção:
1) Converter moeda
2) Ver taxas de câmbio
3) Sobre o sistema
4) Sair

> Digite sua opção: 1

Digite o valor: 100
De (BRL): 
Para (ARS): 
Resultado: R$ 100,00 BRL = $ 2.800,00 ARS

* Principais Bibliotecas
Dependência	Descrição
Spring Boot Starter	Framework principal para configuração rápida
Lombok	Anotações para reduzir boilerplate
Gson	Serialização e parsing JSON
JANSI	Cores no terminal (ANSI escape)
JLine	Leitura avançada de terminal


++++
  Observação
++++

Para usar a versão completa da ExchangeRate-API, registre uma conta gratuita em exchangerate-api.com e adicione sua chave no .env.
*******
-- + Desenvolvido por Herivelto Batista Coutinho(ONE). + --
