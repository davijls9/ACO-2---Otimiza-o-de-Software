# Ant Colony Optimization (ACO) Algorithm

Este é um algoritmo de Otimização por Colônia de Formigas (Ant Colony Optimization - ACO) implementado em Python.

## Descrição

O algoritmo ACO é uma técnica inspirada no comportamento de formigas para resolver problemas de otimização, como o Problema do Caixeiro Viajante.

## Funcionamento

O algoritmo utiliza uma população de formigas que constroem soluções para o problema, deixando feromônio em caminhos percorridos. As formigas escolhem seus caminhos com base na quantidade de feromônio e em heurísticas específicas.

## Código 1

Este código contém uma classe `AntColonyOptimization` que implementa o algoritmo ACO.

### Funcionalidades

- `calculate_distance(city_a, city_b)`: Calcula a distância entre duas cidades.
- `update_pheromone()`: Atualiza o feromônio depositado pelas formigas.
- `choose_next_city(ant, current_city)`: Escolhe a próxima cidade a ser visitada pela formiga.
- `ACO_run()`: Executa o algoritmo ACO.
- `plot_results()`: Plota o melhor caminho encontrado.
- `print_results()`: Exibe o melhor caminho e sua distância.
- `calculate_MQ()`: Calcula a Qualidade de Modularização (MQ).
- `show_ant_paths()`: Mostra os caminhos percorridos pelas formigas.
- `show_ant_paths_with_best()`: Mostra os caminhos das formigas com o melhor caminho.

### Uso

Para utilizar o código, basta instanciar a classe `AntColonyOptimization` com os parâmetros desejados e chamar o método `ACO_run()`.

## Código 2

Similar ao Código 1, este também contém uma classe `AntColonyOptimization` para o algoritmo ACO, com funcionalidades semelhantes e utilização parecida.

### Diferenças

- Os parâmetros e configurações podem variar entre os códigos.
- Implementações específicas podem ser encontradas em métodos como `update_pheromone()` e `choose_next_city()`.

## Importante

Ambos os códigos dependem da definição de uma matriz de distâncias, número de formigas, iterações, entre outros parâmetros específicos para o problema em questão.

**Nota:** Certifique-se de definir corretamente os parâmetros e a matriz de distâncias antes de executar os códigos.

Para mais informações sobre os métodos e uso, consulte o código fonte.

## Autor

# Davi J. Leite Santos

### Contato
🏠 Ribeirão das Neves, Minas Gerais - Brasil
📱 (31) 9 9970-8722 (Mobile)
📧 davi.jls@outlook.com
🌐 [LinkedIn](https://www.linkedin.com/in/davi-j-leite-santos)
🌐 [Website](http://davijls.com.br/)
