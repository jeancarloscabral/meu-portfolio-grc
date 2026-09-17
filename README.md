# 🛡️ Portfólio de GRC & Gestão de Riscos Corporativos
Simulação de Governança, Risco e Conformidade (GRC) aplicada a uma empresa fictícia, utilizando frameworks internacionais de mercado (**NIST CSF**) e conformidade com a **LGPD**.

---

## 📋 1. Visão Geral do Projeto
Este repositório tem como objetivo demonstrar a capacidade de traduzir riscos técnicos de TI em decisões de negócio, estruturando inventários de ativos, matrizes de impacto/probabilidade e planos de tratamento alinhados às melhores práticas globais de segurança da informação.

---

## ⚙️ 2. Mapeamento com o NIST CSF (Cybersecurity Framework)
Na gestão de GRC, os controles e riscos não ficam soltos; eles seguem as 5 funções do NIST CSF:

1. **Identify (Identificar):** Mapeamento de ativos críticos e inventário de dados.
2. **Protect (Proteger):** Implementação de barreiras preventivas (ex: MFA, políticas de acesso).
3. **Detect (Detectar):** Monitoramento de incidentes e anomalias.
4. **Respond (Responder):** Ações imediatas após a confirmação de uma ameaça ou vazamento.
5. **Recover (Recuperar):** Planos de contingência e restauração de sistemas (ex: backups offline).

---

## 📊 3. Matriz de Riscos (Exemplo Prático)
Abaixo está o resumo dos riscos mapeados na nossa planilha de controle:

| ID do Risco | Ativo Afetado | Ameaça / Vulnerabilidade | Prob (1-5) | Imp (1-5) | Nível do Risco | Função NIST | Plano de Tratamento / Mitigação |
| :--- | :--- | :--- | :---: | :---: | :---: | :--- | :--- |
| **R001** | Banco de Dados de Clientes | Vazamento por credencial fraca / Phishing | 4 | 5 | **20 (Crítico)** | Protect | Implementar Autenticação Multifator (MFA) e treinamento de conscientização. |
| **R002** | Notebooks Corporativos | Roubo ou extravio de hardware externo | 3 | 4 | **12 (Moderado)** | Protect | Ativar criptografia de disco (BitLocker) e bloqueio remoto. |
| **R003** | Servidores de Produção | Ataque de Ransomware / Criptografia maliciosa | 3 | 5 | **15 (Alto)** | Recover | Implementar política de backups imutáveis e isolados (Air-Gap). |

---

## ⚖️ 4. Conformidade e LGPD
* **Minimização de Dados:** Garantir que a empresa colete apenas os dados estritamente necessários dos clientes.
* **Gestão de Incidentes:** Protocolo de comunicação com a ANPD (Autoridade Nacional de Proteção de Dados) e titulares em até 72 horas em caso de vazamento de dados pessoais.

---
*Autor: Desenvolvido como parte do portfólio prático de transição para a carreira em Segurança da Informação / GRC.*