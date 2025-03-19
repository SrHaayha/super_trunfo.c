Comentários importantes:
As variáveis são utilizadas para armazenar as informações de cada carta.
O programa solicita ao usuário que insira os dados para as duas cartas (estado, código, cidade, população, área, PIB e pontos turísticos).
A densidade populacional e o PIB per capita são calculados e exibidos ao final para ambas as cartas.
Cada dado inserido e calculado é exibido ao usuário para conferência.
Instruções no README.md:
No arquivo README.md, você deve incluir as instruções de compilação e execução do programa, além de exemplos de uso dos menus e explicação dos atributos disponíveis para comparação.

# Super Trunfo - Comparação de Cartas de Cidades

Este programa implementa a comparação de cartas de cidades com base em atributos como população, área, PIB, entre outros. O jogador pode cadastrar os dados de duas cartas e visualizar as informações detalhadas de cada uma delas.

## Como compilar

Para compilar o programa, utilize um compilador de C como `gcc`. Siga os seguintes passos:

1. Abra o terminal.
2. Navegue até o diretório onde o arquivo `super_trunfo.c` está salvo.
3. Execute o seguinte comando para compilar:

```bash
gcc super_trunfo.c -o super_trunfo

./super_trunfo

Insira os dados da Carta 1:
Estado (letra de A a H): A
Código da Carta (ex: A01): A01
Nome da Cidade: São Paulo
População: 12300000
Área (em km²): 1521.11
PIB (em bilhões de reais): 699
Número de Pontos Turísticos: 15

Insira os dados da Carta 2:
Estado (letra de A a H): B
Código da Carta (ex: B02): B02
Nome da Cidade: Rio de Janeiro
População: 6748000
Área (em km²): 1200.27
PIB (em bilhões de reais): 361
Número de Pontos Turísticos: 20

O programa calculará e exibirá a densidade populacional e o PIB per capita de cada cidade, mostrando as informações completas das cartas.

Atributos das Cartas
As cartas de cidades possuem os seguintes atributos:

Estado: Representado por uma letra de A a H.
Código da Carta: Um código no formato A01, B02, etc.
Nome da Cidade: Nome da cidade cadastrada.
População: Número total de habitantes.
Área: Tamanho da cidade em quilômetros quadrados.
PIB: Produto Interno Bruto da cidade em bilhões de reais.
Número de Pontos Turísticos: Quantidade de pontos turísticos disponíveis.
Densidade Populacional: Calculado automaticamente com base na população e área.
PIB per Capita: Calculado automaticamente com base no PIB e na população.


### Conclusão

Com estas instruções, o usuário saberá como compilar, executar o programa e entender o que esperar na saída. Certifique-se de ajustar o nome do arquivo `super_trunfo.c` conforme o nome do seu código.
