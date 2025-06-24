# 📊 Relatório de Implementação de Serviços AWS
**Data:** 2025-06-24  
**Empresa:** Abstergo Industries  
**Responsável:** Quintino Medeiros

---

## 🧭 Introdução

Este relatório apresenta o processo de implementação de ferramentas na empresa **Abstergo Industries**, realizado por **Quintino Medeiros**.  
O objetivo do projeto é descrever **três serviços AWS** que visam promover a **redução imediata de custos operacionais e computacionais**, mantendo a segurança e o desempenho das soluções utilizadas pela empresa farmacêutica.

---

## 🛠️ Descrição do Projeto

O projeto foi estruturado em **três etapas**, cada uma com foco em um serviço específico com impacto direto na economia de recursos computacionais e financeiros.

---

### ✅ Etapa 1:
- **💾 Amazon S3 Intelligent-Tiering**
- **Foco:** Armazenamento de documentos científicos e arquivos regulatórios
- **Descrição de caso de uso:**  
  A empresa armazena milhões de documentos e amostras clínicas que são raramente acessados, mas precisam ser mantidos por anos por questões legais. O S3 Intelligent-Tiering permite que esses dados sejam movidos automaticamente entre camadas de armazenamento conforme o acesso.

- **Benefícios e diminuição de custos estimada:**  
  💸 Redução de até **40% nos custos de armazenamento** anual  
  📉 Diminuição do desperdício com armazenamento em camadas mais caras  
  📦 Armazenamento automatizado e sem necessidade de scripts ou ações manuais

---

### ✅ Etapa 2:
- **🧠 AWS Compute Optimizer**
- **Foco:** Otimização de instâncias EC2 e EBS
- **Descrição de caso de uso:**  
  Após análise das cargas de trabalho da equipe de P&D e BI, foi possível detectar diversas instâncias EC2 superdimensionadas. O Compute Optimizer utiliza machine learning para sugerir tipos e tamanhos ideais de instância com base no uso real.

- **Benefícios e diminuição de custos estimada:**  
  💸 Economia média de **25% nas faturas EC2 e EBS**  
  ⚙️ Menos sobrecarga de CPU ociosa  
  📊 Instâncias otimizadas com base em dados reais de performance  

---

### ✅ Etapa 3:
- **🧊 AWS Lambda**
- **Foco:** Redução de servidores em tarefas agendadas e automatizadas
- **Descrição de caso de uso:**  
  A empresa realizava diversas tarefas agendadas (geração de relatórios, ETLs, rotinas de auditoria) em servidores EC2 full-time. A migração dessas tarefas para **Lambda Functions** eliminou a necessidade de manter servidores ligados 24/7.

- **Benefícios e diminuição de custos estimada:**  
  💸 Redução de **até 70%** em tarefas computacionais event-driven  
  🚫 Eliminação de custos com servidores ociosos  
  🔄 Escalabilidade automática sem intervenção manual  

---

## 🧾 Conclusão

A implementação das ferramentas **Amazon S3 Intelligent-Tiering**, **AWS Compute Optimizer** e **AWS Lambda** permitiu à **Abstergo Industries** obter uma **redução acumulada estimada de até 45% nos custos mensais em nuvem**, além de otimizar seu uso de recursos computacionais.

Essas ações fortalecem o compromisso da empresa com inovação, sustentabilidade financeira e eficiência técnica em seus ambientes em nuvem.

---

## 📅 Data e Assinatura do Responsável

**Data:** 24 de junho de 2025  
**Responsável:**  
👨🏻‍💻 Quintino Medeiros  
[GitHub](https://github.com/quintinomedeiros) • [LinkedIn](https://www.linkedin.com/in/quintinomedeiros)

---

## 📚 Referências

- [Amazon S3 Intelligent-Tiering](https://docs.aws.amazon.com/AmazonS3/latest/userguide/storage-class-intelligent-tiering.html)  
- [AWS Compute Optimizer](https://aws.amazon.com/compute-optimizer/)  
- [AWS Lambda](https://docs.aws.amazon.com/lambda/latest/dg/welcome.html)  
- [AWS Pricing Calculator](https://calculator.aws.amazon.com/)

---

![AWS Logo](https://a0.awsstatic.com/libra-css/images/logos/aws_logo_smile_1200x630.png)
