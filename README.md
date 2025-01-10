# 📘 Resumo-do-lab-dio
## Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO Microsoft AZ-900
---
No curso Formação Microsoft AZ-900 da DIO, aprendi os fundamentos da computação em nuvem e seus benefícios. Entendi as diferenças entre os modelos de nuvem:

**Nuvem Pública:** Recursos compartilhados acessados pela internet, com maior escalabilidade e menor custo inicial gerando assim economia e flexibilidade. 

**Nuvem Privada:** Exclusiva para uma organização, com maior controle e segurança. Exemplos: governo e empresas financeiras como bancos.

**Nuvem Híbrida:** Integra nuvens pública e privada, combinando flexibilidade e eficiência.


**CAPEX (Capital Expenditure):** Despesas de capital com investimentos iniciais em infraestrutura. Embora ofereça controle sobre os data-centers, tem menos previsibilidade nos gastos a longo prazo. Fica sob responsabilidade da empresa os custos com operação.

**OPEX (Operational Expenditure):** Custos operacionais contínuos, como pagamento pelo uso de serviços de nuvem. Este modelo é mais previsível, facilitando o planejamento financeiro. Exemplos: contas de luz e água.
Além disso, explorei o modelo baseado em consumo (paga-se apenas pelo que se usa), o conceito de Azure Bastions (acesso remoto seguro) e o significado de versão prévia, que são funcionalidades em fase de testes antes do lançamento oficial.

---

**Escalabilidade:** Aprendi como o Azure permite aumentar ou reduzir recursos automaticamente para atender às demandas, garantindo performance mesmo em picos de utilização (Crescimento vertical para atender demandas do servidor).

**Elasticidade:** Entendi como alocar recursos dinamicamente, ajustando a infraestrutura conforme necessário, sem desperdício de custos (Crescimento horizontal para atender demandas de acesso. Ex: Black Friday).

**Confiabilidade:** Vi como o Azure assegura alta disponibilidade e recuperação de desastres, mantendo os serviços ativos mesmo em falhas.

**Previsibilidade:** Explorei como planejar e monitorar o uso de recursos para prever custos e capacidade, otimizando a gestão do ambiente.

**Segurança:** Estudei as ferramentas do Azure para proteção de dados, autenticação, e gerenciamento de identidades, garantindo conformidade com normas de segurança.

**SLA (Service Level Agreement):** Mostra os níveis de serviço oferecidos pelo Azure, como métricas de disponibilidade (ex.: 99,9%), os compromissos em caso de falhas e categoria de valores para cada faixa de disponibilidade. 

---

O Microsoft Azure oferece três principais modelos de serviços em nuvem que atendem a diferentes necessidades de negócios:

**1. IaaS (Infrastructure as a Service)**
É o modelo mais básico de serviços em nuvem, que fornece infraestrutura virtualizada, como servidores, armazenamento e redes, de maneira flexível e escalável.  Controle completo da infraestrutura. Ideal para administradores e desenvolvedores que precisam de flexibilidade. Contudo, impacta em maior responsabilidade de atualizações e monitoramento.

**2. PaaS (Platform as a Service)**
Fornece uma plataforma completa para desenvolvimento, execução e gerenciamento de aplicativos sem a complexidade de gerenciar infraestrutura subjacente. Inclui sistemas operacionais, servidores de banco de dados, serviços de inteligência artificial e ferramentas de desenvolvimento. Fornece ambiente de teste e implantação de aplicativos de softwares. Agilidade no desenvolvimento de software com menos preocupação com infraestrutura. Focado em desenvolvedores.

**3. SaaS (Software as a Service)**
Modelo no qual aplicativos são entregues pela internet como serviços totalmente gerenciados. O provedor cuida da infraestrutura, plataformas e software. Os usuários acessam os aplicativos diretamente via navegador ou APIs, sem a necessidade de instalação ou manutenção. O modelo de licença adquirido determina quem vê o quê. Feito por modelo de assinatura. Teams e Microsoft 365 são alguns exemplos. Se destaca pela simplicidade para os usuários finais. Soluções prontas para uso sem necessidade de gerenciamento técnico.

---

 **Pares de Região**
As regiões do Azure são organizadas em pares de região, compostos por duas regiões dentro da mesma geografia, como Brasil Sul e EUA Leste.
Esses pares garantem redundância e recuperação de desastres, oferecendo replicação automática de dados em serviços.
Em caso de interrupções, o Azure prioriza a recuperação de uma região dentro do par, garantindo maior resiliência.

**Grupos de Recursos**
Um grupo de recursos é um contêiner lógico no qual os recursos do Azure (como máquinas virtuais, bancos de dados e redes) são organizados.
Ele facilita o gerenciamento coletivo, como monitoramento, controle de custos e aplicação de políticas.
Recursos dentro do grupo podem ser movidos ou excluídos em conjunto, simplificando a administração.

**Assinatura da Azure**
Uma assinatura é a unidade que conecta os serviços do Azure ao faturamento.
Ela permite acessar e utilizar recursos, com o consumo sendo cobrado de acordo com o modelo escolhido.
As assinaturas podem ser gerenciadas separadamente para diferentes projetos ou departamentos, possibilitando maior controle sobre custos e acessos.

**Grupos de Gerenciamento**
São estruturas hierárquicas que ajudam a organizar múltiplas assinaturas do Azure.
Permitem aplicar políticas, restrições e configurações em várias assinaturas de forma centralizada.
Útil para grandes organizações que precisam de governança em larga escala, agrupando assinaturas por departamentos ou áreas de negócio.

