# Registro_Clientes📝
Atividade da faculdade desenvolvida em linguagem C, com o objetivo de criar um sistema de registro de clientes utilizando conceitos de ponteiros e alocação dinâmica de memória que contenha as seguintes funcionalidades:

- Incluir um novo cliente (Com um limite de 10 cadastros)

- Remover cliente - atualizar o montante de compras do cliente realizadas no mês corrente

- Zerar todos os montantes de compras por ocasião da virada de mês

- Listar o cliente melhor comprador

- Exibir um montante de compras de um cliente específico.

O programa prevê a situação que a quantidade de clientes a ser cadastrados supere a previsão inicial. Neste caso, quando o espaço de memória destinado a receber dados dos clientes estiver cheia, amplia-se esse espaço sempre em blocos de 10. Nesse sistema foi utilizado a função Calloc que permite armazenar um determinado numero de espaços para armazenamento de dados na memória e a função Realloc que realoca espaços atribuidos em calloc garantindo sua flexibilização
