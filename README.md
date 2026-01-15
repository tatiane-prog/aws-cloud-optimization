# Relatório de Implementação de Serviços AWS - Otimização de Custos

**Data:** 14 de Janeiro de 2026  
**Empresa:** Abstergo Industries  
**Responsável:** Tatiane Mares Oliveira

---

## 1. Introdução
Este relatório apresenta o processo de implementação de ferramentas na nuvem da **Amazon Web Services (AWS)** realizado para a empresa Abstergo Industries. O foco principal deste projeto é a seleção estratégica de três serviços que permitem a redução imediata de custos operacionais e o aumento da eficiência na gestão de dados.

## 2. Descrição do Projeto
O projeto foi estruturado em três etapas fundamentais, focando em armazenamento, computação e gestão de bancos de dados. Abaixo, detalho cada ferramenta escolhida e o seu respetivo caso de uso:

### Etapa 1: AWS S3 (Simple Storage Service)
* **Foco da ferramenta:** Armazenamento de objetos escalável e de alta durabilidade.
* **Caso de Uso:** Substituição de servidores de arquivos físicos por armazenamento em nuvem. A implementação utiliza políticas de ciclo de vida (S3 Lifecycle) para mover automaticamente dados antigos ou pouco acessados para classes de armazenamento de menor custo (como S3 Glacier), reduzindo drasticamente os gastos com backups e logs de longo prazo.

### Etapa 2: AWS Lambda
* **Foco da ferramenta:** Computação sem servidor (Serverless).
* **Caso de Uso:** Automação de tarefas de backend e processamento de dados sem a necessidade de manter servidores ligados 24/7. Como a cobrança é feita apenas por milissegundos de execução, o Lambda elimina o custo de infraestrutura ociosa, sendo ideal para scripts de limpeza de bases de dados e integração de APIs.

### Etapa 3: Amazon RDS (Relational Database Service)
* **Foco da ferramenta:** Serviço de banco de dados relacional totalmente gerenciado.
* **Caso de Uso:** Migração de bancos de dados locais para um ambiente que reduz o custo de manutenção de hardware e administração (DBA). Ao utilizar "Instâncias Reservadas" para cargas de trabalho estáveis, a empresa pode obter economias significativas em comparação com instâncias sob demanda, garantindo alta performance para sistemas de produção.

## 3. Conclusão
A implementação destes serviços na Abstergo Industries visa consolidar uma infraestrutura moderna e económica. A transição para o modelo de pagamento por uso (pay-as-you-go) e a automação de processos garantem que a empresa reduza desperdícios financeiros e possa escalar as suas operações de dados de forma sustentável. Recomenda-se a monitorização contínua através do *AWS Cost Explorer* para identificar novas oportunidades de otimização.

---
*Relatório gerado para fins académicos e de demonstração técnica.*
 aws-cloud-optimization
Projeto de análise e implementação de serviços AWS voltado para a otimização de custos e eficiência operacional em infraestrutura de nuvem.
