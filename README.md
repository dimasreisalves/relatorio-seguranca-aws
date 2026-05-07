# RELATÓRIO DE IMPLEMENTAÇÃO DE MEDIDAS DE SEGURANÇA  
**Data:** 07/05/2026  
**Empresa:** Abstergo Industries  
**Responsável:** Dimas  

---

## Descrição do Projeto  
O projeto de implementação de ferramentas foi dividido em 3 medidas de segurança. A seguir, serão descritas as etapas da implementação:

---

### Medida 1: Controle de Acesso com IAM  
- Implementação de políticas de acesso utilizando o **AWS Identity and Access Management (IAM)**.  
- Garantia de que cada usuário ou serviço possua apenas as permissões necessárias (princípio do menor privilégio).  
- Uso de autenticação multifator (MFA) para reforçar a segurança de contas críticas.  

---

### Medida 2: Proteção de Dados com Criptografia  
- Utilização do **AWS Key Management Service (KMS)** para gerenciar chaves de criptografia.  
- Criptografia de dados em repouso (S3, RDS, EBS) e em trânsito (TLS/SSL).  
- Adoção de boas práticas para evitar vazamento de informações sensíveis.  

---

### Medida 3: Monitoramento e Auditoria Contínua  
- Configuração do **AWS CloudTrail** para registrar todas as ações realizadas na conta.  
- Uso do **Amazon CloudWatch** para monitorar métricas e gerar alertas em tempo real.  
- Implementação de auditorias periódicas para identificar comportamentos suspeitos e corrigir falhas.  

---

## Conclusão  
A implementação dessas medidas de segurança na AWS Cloud é essencial para proteger dados, aplicações e infraestrutura contra ameaças internas e externas. O uso de controles de acesso, criptografia e monitoramento contínuo fortalece a postura de segurança da empresa, garantindo conformidade e maior confiança no uso da nuvem.  

---

## 📌 Referências  
- [AWS IAM](https://aws.amazon.com/iam/)  
- [AWS KMS](https://aws.amazon.com/kms/)  
- [AWS CloudTrail](https://aws.amazon.com/cloudtrail/)  
- [Amazon CloudWatch](https://aws.amazon.com/cloudwatch/)  
