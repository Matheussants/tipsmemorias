# tipsmemorias
Conceitos memória ram, memória rom, swap e paginação de memória

- Memória RAM 
  A memória RAM (Random Access Memory - Memória de Acesso Aleatório) é um hardware de armazenamento randômico e volátil de memória. Isto significa que esta peça armazena dados de programas em execução enquanto o computador está ligado.

  A memória RAM é de acesso rápido, ou seja, é essencial para acompanhar a velocidade do processador. Este tipo de memória recebe as informações do HD, e as armazena temporariamente, disponibilizando este conteúdo ao processador. Seria muito mais lenta a execução de um programa caso o processador tivesse que procurar os dados diretamente do HD.

  ![memoria-ram-1](https://cloud.githubusercontent.com/assets/27031498/26278544/54898f1c-3d73-11e7-9fef-ed7292b6be7a.jpg)


- Memória ROM 
  O termo memória ROM se refere a uma memória de armazenamento que permite apenas a leitura da informação e não de sua destruição, independente da presença ou não de uma fonte de energia que a alimente.

  ROM é uma sigla em inglês que se refere ao termo “Read Only Memory” ou “Memória de Apenas uma Leitura”. Trata-se de uma memória de semicondutor que facilita a conservação da informação que pode ser lida, mas que não pode ser destruída. Diferentemente da memória RAM, os dados contidos em uma memória ROM não são destruídos nem perdidos em caso de interrupção da energia elétrica, por isso, é chamada de “memória não volátil”.
  
 ![rom](https://cloud.githubusercontent.com/assets/27031498/26278546/54961e44-3d73-11e7-85d2-964db200629a.jpg)


- Memória Swap
  Podemos dizer que seja uma técnica computacional usada pelos sistemas operacionais para aumentar quantidade de memória real do computador a fim de rodar os programas e o próprio sistema sem travamentos.

  Essa memória virtual que vai auxiliar a memória RAM fica armazenada no seu HD e tem diferenças de sistema para sistema, porém cumpre a mesma função.
  
 ![memoria-swap](https://cloud.githubusercontent.com/assets/27031498/26278545/548bddc6-3d73-11e7-814e-71f751c3f98d.png)
  
  
 - Memória páginada
  No contexto dos sistemas operacionais, a paginação da memória do computador é um processo de virtualização da memória que consiste na subdivisão da memória física em pequenas partições (frames), para permitir-lhe uma utilização mais eficiente. As frames da memória física correspondem a páginas de memória virtual. A alocação de memória é requisitada por páginas, a menor unidade deste método. Cada página é mapeada numa frame de memória através de um processo que chama paginação.[1]

  A paginação é implementada normalmente por unidades dedicadas de hardware integradas nos processadores. No caso dos processadores da família Intel x86, esta funcionalidade está atribuída à MMU. A paginação é obtida através de consulta a tabelas que relacionam os endereços lineares das páginas de memória com os endereços físicos das frames de memória respectivas.
  
  ![gerenciamento-de-memoria-paginada](https://cloud.githubusercontent.com/assets/27031498/26278552/6fd6552a-3d73-11e7-8fa3-8a8e6f537e35.jpg)
  
  
  
