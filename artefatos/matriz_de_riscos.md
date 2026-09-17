# Matriz de Análise de Riscos e Tratamento (NIST CSF - Identify & Protect)

Simulação prática de avaliação de riscos aplicada aos ativos críticos da empresa fictícia do portfólio.

## 📊 Tabela de Riscos e Controles

| Ativo Crítico | Ameaça / Vulnerabilidade | Impacto (1-5) | Probabilidade (1-5) | Nível de Risco | Plano de Tratamento / Mitigação (NIST) |
| :--- | :--- | :---: | :---: | :---: | :--- |
| **Banco de Dados de Clientes (PII)** | Vazamento de dados por credencial de acesso comprometida. | 5 (Crítico) | 2 (Baixa) | **Médio / Alto** | Implementação de MFA obrigatório e criptografia AES-256 em repouso (Proteção). |
| **Servidor de Produção** | Indisponibilidade por ataque de Ransomware. | 5 (Crítico) | 3 (Média) | **Alto** | Rotina de backups diários isolados (Air-Gap) e plano de resposta a incidentes (Recuperação). |
| **Dispositivos Móveis dos Colaboradores** | Perda ou furto de notebook corporativo sem criptografia. | 3 (Moderado) | 3 (Média) | **Médio** | Instalação de política de disco criptografado (BitLocker) e wipe remoto. |

---

## 🛠️ Metodologia Utilizada
* **Identificação:** Mapeamento de ativos essenciais para a operação e conformidade com a **LGPD**.
* **Avaliação:** Cruzamento entre o impacto regulatório/financeiro e a probabilidade de ocorrência.
* **Tratamento:** Aplicação de controles preventivos e corretivos baseados nas diretrizes do **NIST CSF**.
