📈 Otimização de Receita: Priorização de Hipóteses e Análise de Testes A/B

---

## 📋 Sumário
- [Descrição do Projeto](#descrição-do-projeto)
- [Objetivos](#objetivos)
- [Resultados](#resultados)
- [Ferramentas Utilizadas](#ferramentas-utilizadas)
- [Aprendizados Técnicos](#aprendizados-técnicos)
- [Melhorias Futuras](#melhorias-futuras)
- [Como Executar](#como-executar)

---

## 📖 Descrição do Projeto
Este projeto foca-se na **otimização da receita** de uma grande loja online através de um processo estruturado de tomada de decisão baseada em dados. O trabalho divide-se em duas etapas críticas:
- **Priorização de hipóteses** utilizando frameworks de pontuação (ICE e RICE).
- **Execução e análise** rigorosa de um Teste A/B para validar o impacto real das mudanças na taxa de conversão e no faturamento.

---

## 🎯 Objetivos
- Ordenar 9 hipóteses de negócio de forma estratégica.
- Demonstrar como o parâmetro de **Alcance (Reach)** no framework RICE altera as prioridades em relação ao ICE.
- Concluir o teste A/B com base em diferenças estatísticas significativas.
- Garantir a estabilidade dos dados e tratar outliers para análises realistas.

---

## 📊 Resultados
- **Priorização Estratégica**: Ordenação de hipóteses evidenciando o impacto do Reach.
- **Decisão de Negócio**: Identificação de diferença significativa na conversão a favor de um grupo.
- **Estabilidade de Dados**: Verificação da convergência de métricas acumuladas.
- **Tratamento de Outliers**: Definição de limites técnicos (percentis 95 e 99) para pedidos extremos.

---

## 🛠️ Ferramentas Utilizadas
- **Linguagem**: Python
- **Bibliotecas Principais**:
  - Pandas (Manipulação de dados)
  - Matplotlib e Seaborn (Visualização)
  - SciPy (Inferência Estatística)
- **Metodologias**:
  - Frameworks ICE e RICE
  - Gráficos de Receita e Conversão Acumulada
  - Teste de Mann-Whitney (U-test) para dados não-paramétricos
- **Ambiente**: VS Code / Jupyter Notebook

---

## 📚 Aprendizados Técnicos
- **Aplicação de Frameworks de Decisão**: Uso de RICE para balancear Impacto, Confiança, Esforço e Reach.
- **Análise de Testes A/B**: Monitorização de métricas cumulativas para evitar conclusões precipitadas.
- **Estatística Não-Paramétrica**: Aplicação do teste de Mann-Whitney para dados com outliers.
- **Deteção de Anomalias**: Uso de percentis para filtrar ruídos e focar no comportamento real.

---

## 🚀 Melhorias Futuras
- **Análise de Coortes**: Integração com LTV para verificar sustentabilidade da conversão.
- **Segmentação de Resultados**: Divisão por dispositivos (Mobile vs Desktop).
- **Automação de Dashboards**: Visualização em tempo real para acompanhar p-value e diferenças.

---

## ▶️ Como Executar
1. Clone o repositório.
2. Instale as dependências: `pip install pandas matplotlib seaborn scipy`.
3. Abra o notebook `revenue-optimization-hypothesis-prioritization-ab-testing.ipynb` no Jupyter.
4. Execute as células sequencialmente.

---

*Projeto desenvolvido como parte do módulo 9 de Data Analytics.*
