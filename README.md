# DIO Desafio - Monitoramento Inteligente com o Azure

Este documento apresenta uma visão clara e prática sobre três pilares importantes da gestão de recursos no **Microsoft Azure**: **Assistente do Azure**, **Integridade do Serviço do Azure** e **Azure Monitor**.

---

## 🤖 Assistente do Azure

O **Assistente do Azure** é uma ferramenta que fornece recomendações proativas para otimizar seus recursos na nuvem.

- **Função principal**:  
  - Consolidar recomendações em uma única exibição.  
  - Melhorar desempenho, segurança e confiabilidade dos recursos.  
  - Reduzir custos com sugestões de otimização.  

- **Integrações**:  
  - Se conecta ao **Microsoft Defender para Nuvem** para fornecer recomendações de segurança.  
  - Trabalha em conjunto com **Azure Monitor** para insights de desempenho.  

- **Exemplo de uso**:  
  - Identificar VMs subutilizadas e recomendar a troca para instâncias menores ou desligamento em horários ociosos.  

---

## 🛡️ Integridade do Serviço do Azure

A **Integridade do Serviço** é composta por três camadas que ajudam você a acompanhar o status dos serviços e recursos:

1. **Status do Azure**  
   - Exibe a saúde global dos serviços do Azure.  
   - Mostra incidentes em tempo real que afetam regiões ou serviços amplamente.  

2. **Integridade do Serviço (Service Health)**  
   - Personalizado para sua assinatura.  
   - Informa sobre incidentes, manutenção planejada e alertas que podem impactar seus recursos.  

3. **Resource Health**  
   - Exibição individual da integridade de cada recurso.  
   - Indica se uma VM, banco de dados ou outro serviço está saudável, degradado ou indisponível.  
   - Ajuda a diagnosticar problemas específicos e tomar ações corretivas.  

👉 Em conjunto, essas três camadas garantem que você esteja informado tanto sobre o status global quanto sobre o impacto direto em seus recursos.

---

## 📊 Azure Monitor

O **Azure Monitor** é o serviço que coleta e analisa telemetria de seus recursos, maximizando disponibilidade e desempenho.

- **Principais funcionalidades**:  
  - Coleta de métricas e logs de aplicativos, VMs, bancos de dados e serviços.  
  - Configuração de alertas proativos para falhas ou degradação de desempenho.  
  - Integração com **Log Analytics** e **Application Insights** para análise avançada.  
  - Dashboards personalizados para monitoramento em tempo real.  

- **Benefícios**:  
  - Detectar problemas antes que impactem usuários finais.  
  - Tomar decisões baseadas em dados para otimizar custos e performance.  
  - Garantir alta disponibilidade de serviços críticos.  

---

## 📌 Conclusão

- O **Assistente do Azure** ajuda a otimizar recursos com recomendações inteligentes.  
- A **Integridade do Serviço** mantém você informado sobre incidentes globais, status da sua assinatura e saúde de recursos individuais.  
- O **Azure Monitor** coleta e analisa telemetria para garantir desempenho e disponibilidade.  

Essas três ferramentas juntas formam a base da **governança, monitoramento e otimização contínua** no Azure.
