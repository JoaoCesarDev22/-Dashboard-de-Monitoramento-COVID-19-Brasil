# 📊 Dashboard de Monitoramento COVID-19 Brasil

<p align="center">
  <img width="1300" alt="DashCovid" src="https://github.com/user-attachments/assets/9ea9abfb-dd1f-47db-ab04-712e22cd4079" />
</p>


## 📝 Descrição do Projeto
Este projeto foi desenvolvido para analisar e monitorar os dados da pandemia de COVID-19 no Brasil. O foco principal foi transformar dados brutos em um painel interativo que permite acompanhar o impacto da doença por regiões e estados, além de visualizar a tendência histórica de novos casos.

O projeto demonstra competências em **ETL**, **Modelagem de Dados Relacional** e **Design de Dashboards (UX/UI)** aplicado à análise de dados de saúde pública.

---

## 🛠️ Tecnologias e Ferramentas
* **Power BI**: Desenvolvimento do dashboard e visualizações.
* **Power Query (ETL)**: Extração, limpeza e transformação dos dados (tratamento de nulos, tipagem e criação de chaves).
* **Modelagem de Dados**: Estruturação em modelo **Star Schema** (Fato x Dimensão).
* **Linguagem DAX**: Criação de medidas calculadas para totalização de óbitos e casos.

---

## ⚙️ O que foi desenvolvido

### 1. Tratamento e Modelagem
* **Limpeza de Dados**: Padronização de nomes de estados e tratamento de datas.
* **Relacionamentos**: Conexão entre a tabela `Fato_Covid` e a tabela `Dim_Estados` para permitir filtragem cruzada eficiente.

### 2. Design e Experiência do Usuário (UX)
* **Paleta de Cores Estratégica**: Uso de **Vermelho** para métricas de alerta (Óbitos) e **Azul** para volume (Casos), com uso de transparências para um visual limpo e moderno.
* **Hierarquia Visual**: Cartões de destaque no topo para leitura rápida, seguidos por rankings detalhados e evolução temporal.

### 3. Funcionalidades de Análise
* **Filtros Dinâmicos**: Segmentação por Unidade Federativa (UF) que atualiza todo o painel.
* **Ranking de Estados**: Destaque para os estados mais afetados (ex: SP e RJ).
* **Análise de Tendência**: Gráfico de linha mostrando as ondas de contágio ao longo dos meses.

---

## 📈 Visualização do Painel
O dashboard contém os seguintes indicadores principais:
* **Total de Óbitos**: Acumulado nacional destacado em vermelho.
* **Total de Casos**: Volume total de casos confirmados.
* **Distribuição Regional**: Óbitos divididos por Regiões do Brasil.
* **Tendência Temporal**: Curva de evolução de novos casos mensais.

---

## 📂 Arquivos do Repositório
* `/Projeto/Atividade_Covid.pbix`: Arquivo fonte do Power BI.
* `/Documentacao/Relatorio_Covid.pdf`: Versão estática para conferência rápida.
* `README.md`: Documentação do projeto.
* `LICENSE`: Termos de uso do projeto (MIT).

---

## 🚀 Como Visualizar
1. Faça o download do arquivo `.pbix` deste repositório.
2. Certifique-se de ter o [Power BI Desktop](https://powerbi.microsoft.com/desktop/) instalado.
3. Abra o arquivo para explorar a interatividade dos filtros e gráficos.

---

<p align="center">
  ⚖️ Licença <b>MIT</b> - Veja o arquivo <a href="./LICENSE">LICENSE</a> para mais detalhes.
  <br>
  Desenvolvido por <b>João César Netto Souza Castro</b>
</p>

---

**Desenvolvido por João César Netto Souza Castro** www.linkedin.com/in/joão-césar-netto-souza-castro-152441304 | [Meu Portfólio]([https://github.com/SEU_USUARIO](https://github.com/JoaoCesarDev22))
