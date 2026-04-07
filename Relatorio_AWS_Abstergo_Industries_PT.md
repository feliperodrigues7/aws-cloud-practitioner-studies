# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

**Data:** 07 de Abril de 2026  
**Empresa:** Abstergo Industries  
**Responsável:** Luiz Felipe Rodrigues de Freitas  

---

## Introdução

Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Luiz Felipe Rodrigues de Freitas. A Abstergo Industries atua como revendedora farmacêutica, distribuindo produtos para outras farmácias, e ainda não possui nenhuma infraestrutura em nuvem.

O objetivo do projeto foi elencar 3 serviços AWS com a finalidade de realizar diminuição de custos imediatos, levando em consideração o perfil da empresa e o baixo nível de familiaridade da gestão financeira com tecnologia em nuvem.

---

## Descrição do Projeto

O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

### Etapa 1:
- **Nome da ferramenta:** Amazon S3 (Simple Storage Service)
- **Foco da ferramenta:** Armazenamento seguro, escalável e de baixo custo para dados e documentos da empresa.
- **Descrição de caso de uso:** A Abstergo Industries lida diariamente com grandes volumes de documentos: notas fiscais, pedidos de compra, contratos com farmácias parceiras e registros de produtos. Atualmente esses arquivos são mantidos em servidores físicos locais com alto custo de manutenção e risco de perda. Com o Amazon S3, toda essa documentação será migrada para a nuvem com armazenamento por demanda — a empresa paga apenas pelo que utiliza — eliminando custos fixos de hardware e garantindo disponibilidade e redundância automática dos dados.

### Etapa 2:
- **Nome da ferramenta:** Amazon RDS (Relational Database Service)
- **Foco da ferramenta:** Banco de dados gerenciado na nuvem para controle de estoque, pedidos e clientes.
- **Descrição de caso de uso:** A gestão de estoque e o rastreamento de pedidos entre a Abstergo Industries e as farmácias clientes exigem um banco de dados confiável e sempre disponível. Com o Amazon RDS, a empresa substitui bancos de dados instalados localmente — que demandam licenças caras, backups manuais e equipe especializada — por uma solução totalmente gerenciada pela AWS, com backups automáticos, atualizações de segurança e escalabilidade conforme o crescimento da operação.

### Etapa 3:
- **Nome da ferramenta:** Amazon SNS (Simple Notification Service)
- **Foco da ferramenta:** Serviço de notificações e mensagens para comunicação automatizada com farmácias parceiras.
- **Descrição de caso de uso:** Atualmente, a comunicação da Abstergo Industries com as farmácias clientes é feita de forma manual (telefone, e-mail avulso), gerando retrabalho e custos operacionais desnecessários. Com o Amazon SNS, é possível automatizar o envio de notificações sobre confirmação de pedidos, atualizações de entrega e alertas de estoque crítico, cobrando apenas por mensagem enviada — sem infraestrutura fixa.

---

## Conclusão

A implementação de ferramentas na empresa **Abstergo Industries** tem como esperado a **redução significativa de custos operacionais de TI, maior agilidade no atendimento às farmácias parceiras e eliminação de gastos com infraestrutura física**, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

---

## Anexos

- Planilha de comparativo de custos: infraestrutura local vs. AWS
- Diagrama de arquitetura dos serviços AWS propostos
- Cronograma de migração e implantação das etapas
- Manual de uso do Amazon S3 para a equipe administrativa
- Política de segurança e controle de acesso (IAM) da AWS

---

**Assinatura do Responsável pelo Projeto:**

Luiz Felipe Rodrigues de Freitas
