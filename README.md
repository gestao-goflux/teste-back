# Teste para vaga de Desenvolvedor Back-end

Olá aspirante a gofluxer, seja bem-vindo ao seu teste.

Esperamos que tenha dado tudo certo até aqui e desejamos a você um ótimo teste.


Disclaimer: Os CNPJs e CPFs utilizados nos testes foram gerados em https://www.4devs.com.br/gerador_de_cnpj

*Obs*: Você pode utilizar frameworks e bibliotecas.

## O Problema e O que Esperamos
Nosso core business é contratação de frete, então nada mais justo do que praticarmos o seu futuro dia-a-dia.

Neste teste você deve:

- Criar uma API REST capaz de cadastrar e obter informações de Embarcadores, Transportadores, Ofertas e Lances;

- Realizar persistência dos dados recebidos num banco de dados criado por você;

- Informar um .sql contendo os a lógica de criação do banco;

- Criar uma documentação para consumo dos endpoints.


## Prazo
O prazo de entrega é de 4 dias corridos, contados a partir do recebimento deste teste.


## Exemplos de Requisições

### Exemplo de JSON de Cadastro de Embarcador
```
{
  "id": 1,
  "name": "goFlux Brasil",
  "doc": "60.429.484/0001-10",
  "about": "goFlux, uma empresa especializada em inovar na contratação de fretes",
  "active": true,
  "site": "https://goflux.com.br/"
}
```
### Exemplo de JSON de Cadastro de Transportador
```
{
  "id": 12,
  "name": "Transportadora Rodoclub",
  "doc": "99.974.145/0001-50",
  "about": "Transportadora Rodoclub, transportando sonhos",
  "active": true,
  "site": "https://goflux.com.br/"
}
```
### Exemplo de JSON de Cadastro de Oferta
```
{
  "id": 1,
  "id_customer": 1,
  "from": "Porto Alegre - RS",
  "to": "São Paulo - SP",
  "initial_value": 130.00,
  "amount": 300.00,
  "amount_type": "TON"
}
```
### Exemplo de JSON de Lance
```
{
  "id_provider": 12,
  "id_offer": 1,
  "value": 105.00,
  "amount": 230.00
}
```


## Entrega
Coloque seu código em um repositório privado no Github e adicione o @gestao-goflux como um de seus colaboradores. Essa conta no Github (gestao-goflux) é utilizada exclusivamente para aplicação e revisão de testes.


## Considerações Finais
Sinta-se livre para impressionar na sua solução e apresentação.

Bom teste!!

#NaVelocidadeDoSeuTalento #EnjoyTheRide
