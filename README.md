### Reduzindo o consumo de energia do Hadoop 3.x MapReduce através do Energy Efficient Ethernet
Dissertação apresentada como requisito parcial à obtenção do grau de Mestre em Informática no Programa de Pós- Graduação em Informática, Setor de Ciências Exatas, da Universidade Federal do Paraná.

**Área de concentração:** Ciência da Computação.

**Orientador:** Luiz Carlos Pessoa Albini.

**Coorientador:** Leandro Batista De Almeida.


**Resumo:** O consumo de energia é um dos maiores desafios na infraestrutura de processamento de Big Data. Atualmente os gastos com energia são ainda maiores do que na aquisição do hardware, representando 75% do custo total dos data centers. Aproximadamente 30% de toda a energia do data center é consumida por switches de rede. O Energy Efficient Ethernet é um padrão recente que visa reduzir o consumo de energia, embora a prática atual na indústria seja desativá-lo em produção, pois pode causar sobrecargas na rede e perda de desempenho. Esta dissertação fornece uma visão geral de como a atual versão do Apache Hadoop, a 3.x, se comporta com o Energy Efficient Ethernet habilitado para links de 1GbE até 400GbE. Os resultados apresentados mostram que há economia de energia significativa com pouca ou nenhuma perda de desempenho para conexões de até 40GbE. No entanto, conexões de 100GbE e 400GbE apresentam perdas significativas de desempenho devido ao despertar do link para transmissões de um único frame.

**Palavras-chave:** Green Networking, Big Data, Energy Efficient Ethernet, MapReduce, Hadoop.

**Para informações adicionais sobre as ferramentas de simulação e tecnologias utilizadas na pesquisa veja:**

- [**YARN Scheduler Load Simulator**](https://hadoop.apache.org/docs/stable/hadoop-sls/SchedulerLoadSimulator.html)
- [**Net Scheduler Load Simulator**](https://github.com/MaxiNet/netSLS)
- [**MaxiNet**](https://github.com/MaxiNet/MaxiNet)
- [**Apache Hadoop**](https://github.com/apache/hadoop)

***NOTA:*** *As informações contidas na dissertação são resultados da nossa pesquisa Reduzindo o consumo de energia do Hadoop 3.x MapReduce através do Energy Efficient Ethernet, do projeto Computação e Comunicação Verde para Processamento de Big Data financiado pelo CNPq - Conselho Nacional de Desenvolvimento Científico e Tecnológico.*
