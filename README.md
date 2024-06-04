# OptiRoute: Efficient Vehicle Routing with Parallel Computing

## Descrição
OptiRoute é uma coleção de algoritmos otimizados para resolver o problema de roteamento de veículos (VRP). Este projeto explora diversas abordagens, incluindo métodos exatos, heurísticas, e paralelização em CPUs e GPUs. A implementação com GPU, utilizando Thrust, destaca-se como a solução mais eficiente, oferecendo tempos de execução significativamente reduzidos para grandes conjuntos de dados. Ideal para aplicações em logística e transporte, OptiRoute demonstra como a computação paralela pode revolucionar a resolução de problemas complexos de otimização.

## Abordagens Implementadas
- **VRPY:** Algoritmo baseado em heurísticas.
- **Busca Exaustiva:** Método exato que explora todas as permutações possíveis.
- **Heurística Clarke-Wright:** Algoritmo rápido e eficiente para grandes instâncias.
- **Paralelo Local:** Utiliza threads para paralelizar a execução em uma única máquina.
- **Paralelo MPI:** Distribui a carga em várias máquinas, utilizando paralelização local.
- **Paralelo GPU (Thrust):** Implementação altamente eficiente usando a biblioteca Thrust da NVIDIA para computação em GPU.

## Configuração do Ambiente
1. **Clonar o repositório:**
    ```bash
    git clone https://github.com/seu-usuario/OptiRoute.git
    cd OptiRoute
    ```

2. **Instalar dependências (para execução no Google Colab):**
    - Certifique-se de que os drivers NVIDIA e o CUDA Toolkit estão instalados.

## Como Executar
### Execução no Google Colab
1. **Abrir o notebook do Google Colab:**
    - [OptiRoute Notebook](link-para-o-notebook)

2. **Configurar a GPU:**
    - Vá para `Runtime` > `Change runtime type` e selecione `GPU`.

3. **Executar as células do notebook:**
    - Siga as instruções no notebook para compilar e executar os diferentes algoritmos.

## Visualização dos Resultados
- O gráfico de comparação dos tempos de execução para diferentes algoritmos pode ser gerado e visualizado diretamente no notebook.

## Contribuições
- Sinta-se à vontade para abrir issues e pull requests para melhorar o OptiRoute.

## Licença
- Este projeto está licenciado sob a MIT License. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.
