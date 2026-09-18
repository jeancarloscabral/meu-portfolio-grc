# Plano de Resposta a Incidentes de Segurança da Informação

## 1. Objetivo
Estabelecer o procedimento padrão a ser seguido pela organização para identificar, conter, mitigar e reportar incidentes de segurança da informação, assegurando a conformidade com as diretrizes do framework **NIST CSF** e com os requisitos da **LGPD (Lei Geral de Proteção de Dados)**.

---

## 2. Classificação de Severidade dos Incidentes
Os incidentes são classificados em três níveis para direcionar a prioridade de resposta:
* **Baixo:** Evento isolado sem impacto crítico ou vazamento de dados (ex: tentativa de acesso bloqueada por firewall).
* **Médio:** Indisponibilidade temporária de sistemas internos ou falha de controle de acesso de menor escala.
* **Alto (Crítico):** Vazamento confirmado de dados pessoais, ataque de ransomware ou indisponibilidade de ativos essenciais para o negócio.

---

## 3. Fases de Resposta a Incidentes (Baseado no NIST CSF)
O ciclo de vida da resposta ao incidente segue as etapas fundamentais de segurança:
1. **Preparação:** Manutenção de políticas atualizadas, treinamentos de conscientização e ferramentas de monitoramento ativas.
2. **Detecção e Análise:** Identificação imediata do alerta, verificação da autenticidade e mensuração do impacto.
3. **Contenção e Erradicação:** Isolamento rápido dos ativos afetados da rede para evitar a propagação da ameaça e eliminação da vulnerabilidade raiz.
4. **Recuperação:** Restauração segura dos sistemas afetados a partir de backups confiáveis e validação da integridade operacional.
5. **Lições Aprendidas:** Realização de reunião pós-incidente para documentar falhas e implementar melhorias preventivas.

---

## 4. Fluxo de Comunicação e Conformidade com a LGPD
* **Notificação Interna:** Acionamento imediato da equipe de TI e da liderança de conformidade (Ganha prioridade em incidentes de nível Médio e Alto).
* **Gestão de Dados Pessoais:** Caso o incidente envolva exposição de dados de titulares, o Encarregado de Proteção de Dados (DPO) deve ser notificado para avaliar a necessidade de comunicação à **ANPD (Autoridade Nacional de Proteção de Dados)** e aos titulares afetados nos prazos legais previstos pela LGPD.
