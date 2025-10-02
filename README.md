<img width="800" height="800" alt="Sem Título-3" src="https://github.com/user-attachments/assets/ba5e532d-6907-4a76-9ce0-6edc4f94ab58" />


# Aprendizado por Projeto Integrado (API) 
Um projeto pedagógico fundamentado na Metodologia API, voltado para o desenvolvimento de competências, baseia-se nos princípios de aprendizado ativo com foco na resolução de problemas reais (RPBL), validação externa e adoção da mentalidade ágil.
A abordagem envolve o uso de estratégias para entender o problema, conceber soluções viáveis e desenvolver um MVP, seguido por sua implementação e operação, conforme os estágios CDIO (Conceber, Desenvolver, Implementar e Operar).


# Equipe
|    Função     | Nome                                  |                                                                                                                                                      GitHub                                                                                                                                                      |
| :-----------: | :------------------------------------ | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| Product Owner | Breno Cesar Conrado|    [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/BrenoConrado15)              |
| Scrum Master  | Gabriel Poffo              |        [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/gabrielpoffo)        |
|  Team Member  | Eduardo Pereira                 |          [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/ddoardo)        |
|  Team Member  | Juan Marcel   |          [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/Juanmarcelg )          |

# Objetivo do Projeto
Este projeto visa identificar as potenciais cargas em movimentação com base em importações e exportações.
#
## Tecnologias Utilizadas
* Canva;
* PowerBI;
* Excel;
* GitHub;
* JiraSoftware;

#

# User Stories e DoR – Dashboard de Segurança Viária

## 1ª Sprint
### User Story 1:

 “Como tomador de decisões públicas, quero receber uma base consolidada de dados de segurança viária, para ter uma visão única e confiável da situação em SP.”

### DoR:

* Base tratada da PRF disponível.
* Base tratada do DATASUS disponível.
* Base tratada do DENATRAN/SENATRAN disponível.
* Base do IBGE disponível (população e frota).
* Estrutura inicial de repositório criada no GitHub.

### User Story 2:
##### Dashboard funcional, aprimorando filtros intuitivos para uso de cliente, como:
 “Como gestor, quero visualizar uma proposta inicial da interface do dashboard, para entender como será a navegação e os principais indicadores.”

### DoR:

* Protótipo não funcional elaborado (wireframe).
* Definição dos indicadores principais para tela inicial (sinistros, óbitos, frota, taxa de motorização).
* Layout inicial documentado (menu, cards, área de gráficos, filtros).
  
    
## 2ª Sprint
### User Story 3:
 “Como tomador de decisão, quero acessar um dashboard inicial com visão geral de SP, para comparar mortes, frota e taxa de motorização.”
  
* Otimização do dashboard - lateralização das informações
* Importações e exportações dentro do estado de São Paulo
* Alteração da descrição de SH4 para apenas código SH4
* Interação de valor agregado por munícipio possibilitando a visão de movimentações SH4 que ainda não foram visualizadas pelo transporte aéreo - oportunidades de movimentação.
  
### User Story 4:
 “Como analista, quero aplicar filtros de ano, região e tipo de veículo, para segmentar os dados conforme minha necessidade.”

### DoR:

* Estrutura de filtros validada.
* Dados categorizados (ano, região administrativa, tipo de veículo, gravidade).
* Mapa interativo de SP disponível para integração.

#

### User Story 5:
 “Como gestor, quero visualizar indicadores-chave (mortalidade por 100 mil habitantes, sinistros por 10 mil veículos), para apoiar decisões estratégicas.”

### DoR:

* Fórmulas de cálculo definidas e validadas.
* Bases integradas para cruzamento (IBGE + DATASUS e DENATRAN + PRF).

#
# 3ª Sprint

### User Story 6:
 “Como pesquisador, quero visualizar a evolução temporal (2015–2025) dos sinistros fatais, para entender tendências.”

### DoR:

* Série histórica organizada e padronizada.
* Gráfico de linhas preparado no Power BI.

#

# User Story 7:
 “Como analista, quero comparar o crescimento da frota com o aumento dos sinistros fatais, para avaliar correlações.”

### DoR:

* Dados da frota por ano consolidados.
* Dados de sinistros fatais por ano consolidados.
* Modelo de correlação definido.



# User Story 8:
 “Como gestor, quero visualizar rankings de regiões mais críticas em taxa de letalidade, para priorizar políticas públicas.”

### DoR:

* Taxas de letalidade calculadas por região administrativa.
* Visualização de ranking disponível no Power BI.

#
# User Story 9:
 “Como usuário final, quero um dashboard intuitivo com documentação, para navegar facilmente e compreender os dados.”

### DoR:

* Layout final revisado e validado.
* Documentação/manual de uso elaborado.
* Navegação testada com casos de uso básicos.


# 

# Backlog do Produto – Dashboard de Segurança Viária

# 1º Sprint

### Criação da base consolidada de dados de segurança viária de SP, construída a partir de fontes públicas:

* PRF – Polícia Rodoviária Federal.
* DATASUS – Ministério da Saúde (informações de mortalidade).
* DENATRAN/SENATRAN – Frota de veículos.
* IBGE – População e taxa de motorização.
* Criação do repositório no GitHub para versionamento do projeto.

### Proposta inicial da interface do dashboard (protótipo não funcional):

* Tela inicial com cards de indicadores principais (sinistros, óbitos, frota, taxa de motorização).
* Menu lateral de navegação (Visão Geral, Mapa, Evolução Temporal).
* Espaço reservado para gráfico de barras/linhas comparativo por ano.
* Área reservada para mapa interativo de SP.
* Filtro superior simulado (Ano, Região Administrativa, Tipo de Veículo).

# 2º Sprint

* Implementação do dashboard inicial no Power BI com visão geral de SP (mortes, frota e taxa de motorização).
* Desenvolvimento do mapa interativo destacando as regiões administrativas de SP com maiores índices de sinistros.
* Inclusão de filtros interativos funcionais: ano, região administrativa, tipo de veículo e gravidade do sinistro.

### Criação de indicadores-chave:

* Mortalidade por 100 mil habitantes (IBGE + DATASUS).
* Sinistros por 10 mil veículos (DENATRAN/SENATRAN + PRF).

# 3º Sprint

* Evolução temporal (2015–2025) dos sinistros fatais em SP.
* Análise da correlação entre crescimento da frota e aumento dos sinistros fatais.
* Visualizações segmentadas por tipo de veículo (motos, carros, caminhões, ônibus etc.).
* Ranking das regiões de SP mais críticas em taxa de letalidade.
* Dashboard final com navegação intuitiva e layout refinado no Power BI.
* Entrega da documentação final (manual de uso para o cliente).
