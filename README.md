## Conversor de Moedas Simples em Java

Este README documenta o código-fonte de um conversor de moedas simples escrito em Java. O programa utiliza a API gratuita `api.exchangerate.host` para obter taxas de conversão em tempo real.

### Funcionalidades

* Permite conversão entre moedas informadas pelo usuário.
* Exibe o resultado da conversão com base na taxa de câmbio obtida da API.

### Requisitos

* Java instalado (versão 8 ou superior recomendada).
* Acesso à internet.

### Como Executar

1. Salve o código como `CurrencyConverter.java`.
2. Abra um terminal ou prompt de comando e navegue até o diretório onde salvou o arquivo.
3. Execute o comando `javac CurrencyConverter.java` para compilar o código.
4. Execute o comando `java CurrencyConverter` para iniciar o programa. 

### Uso

1. O programa solicitará que você informe a moeda de origem (por exemplo, BRL).
2. Em seguida, solicitará a moeda de destino (por exemplo, USD).
3. Por fim, solicitará a quantidade a ser convertida.
4. O programa consultará a API e exibirá o valor convertido na moeda de destino.

### Exemplo

```
Type currency to convert from
BRL
Type currency to convert to
USD
Type quantity to convert
100
1.8628
```

Neste exemplo, o programa converte 100 Reais (BRL) para Dólares Americanos (USD), resultando em aproximadamente 1.86 USD (de acordo com a taxa de câmbio obtida no momento da execução).

### Limitações

* O programa utiliza uma API externa que pode sofrer alterações ou indisponibilidade.
* O programa não considera taxas bancárias ou outras flutuações cambiais que possam ocorrer.

### Contribua

Este é um código-fonte simples e pode ser expandido para incluir funcionalidades adicionais, como:
* Histórico de conversões.
* Interface gráfica.
* Suporte a mais moedas.

Se você quiser contribuir, sinta-se à vontade para fazer um fork do repositório e enviar um pull request.
