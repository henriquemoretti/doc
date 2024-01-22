# Documentação de Apresentação do Datalake

Olá e seja bem-vindo à documentação do Datalake que estamos configurando para você! Aqui está uma visão geral das ferramentas e tecnologias escolhidas para construir um sistema robusto de gerenciamento de dados.

## 1. Sistema Operacional

Utilizaremos o Oracle Linux 9 na sua VM como sistema operacional base. Isso proporciona uma base estável e confiável para as operações do datalake.

## 2. Armazenamento de Dados

O formato de armazenamento escolhido para dados relacionais será o **Parquet**. Este formato de coluna otimiza a leitura analítica e oferece uma excelente compressão para economia de espaço.

## 3. Processamento Distribuído

Para realizar operações distribuídas nos dados, implementaremos o **Apache Spark**. Esta ferramenta é conhecida por sua eficiência no processamento distribuído em grandes conjuntos de dados.

## 4. Consulta SQL

Facilitaremos consultas SQL em grandes conjuntos de dados usando o **Apache Hive**. O Hive proporciona uma interface SQL familiar e é especialmente útil para dados armazenados no Hadoop.

## 5. Modelagem e Estrutura de Dados

Será importante pensar na organização das tabelas no Hive. Recomenda-se considerar a estratégia de particionamento para otimizar consultas e melhorar o desempenho.

## 6. Configurações de Compressão

Exploraremos diferentes algoritmos de compressão disponíveis para o formato Parquet, visando encontrar o equilíbrio ideal entre desempenho e economia de espaço.

## 7. Backup e Segurança

Para backups regulares dos dados, sugerimos a utilização do `distcp` do Hadoop para cópias entre clusters. Além disso, é fundamental garantir boas práticas de segurança na VM, incluindo firewalls e autenticação forte.

## 8. Integração Spark e Hive

Configuraremos a integração entre o Spark e o Hive, aproveitando o Spark SQL para facilitar operações SQL em dados distribuídos.

Lembramos que a eficácia do datalake dependerá da correta configuração e ajuste dessas ferramentas de acordo com as necessidades específicas do seu ambiente e caso de uso.

Estamos aqui para ajudar em qualquer dúvida ou ajuste necessário. Boa jornada no mundo dos dados!