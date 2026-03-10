<h1 align="center"> 🔵Telecom X - Análise de Evasão de Clientes🔵</h1>

<div align="center">
  
## 🛠️ Tecnologias Utilizadas

<div align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" height="40" alt="Python"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" height="40" alt="Pandas"/>
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" height="40" alt="Jupyter"/>
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" height="40" alt="GitHub"/>
  <img src="https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge&logo=python&logoColor=white" height="40" alt="Matplotlib"/>
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" height="40" alt="NumPy"/>
  <img src="https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge&logo=python&logoColor=white" height="40" alt="Seaborn"/>
  <img src="https://img.shields.io/badge/Requests-2CA5E0?style=for-the-badge&logo=python&logoColor=white" height="40" alt="Requests"/>
  <img src="https://img.shields.io/badge/Google%20Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white" height="40" alt="Google Colab"/>
  <img src="https://img.shields.io/badge/Markdown-000000?style=for-the-badge&logo=markdown&logoColor=white" height="40" alt="Markdown"/>
</div>

## 📋 Sobre o Projeto

Este projeto tem como objetivo analisar a evasão de clientes (churn) da Telecom X, uma empresa de telecomunicações que enfrenta altos índices de cancelamento. A partir de uma base com 7.043 clientes, foram aplicadas técnicas de ETL (Extração, Transformação e Carga) e Análise Exploratória de Dados (EDA) para identificar os principais fatores associados ao cancelamento dos serviços.
<div align="center">

## 🔍 Principais Insights

<!-- Distribuição do Churn -->
<table>
  <tr>
    <td width="50%" valign="top">
      <h4>📊 Distribuição do Churn</h4>
      <table>
        <tr><th align="center">Status</th><th align="right">Clientes</th><th align="right">Percentual</th></tr>
        <tr><td align="center">Não cancelaram</td><td align="right">5.174</td><td align="right">73,5%</td></tr>
        <tr><td align="center">Cancelaram</td><td align="right">1.869</td><td align="right">26,5%</td></tr>
      </table>
    </td>
    <td width="50%" valign="top" align="center">
      <h4>🍕 Gráfico Pizza</h4>
      <pre style="font-size: 16px;">
Não cancelaram: ████████████████████████████████████████████████████░░ 73,5%
Cancelaram:     ████████████████████████░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░ 26,5%
      </pre>
      <p><i>█ = percentual | ░ = restante</i></p>
    </td>
  </tr>
</table>

<!-- Comparativo: Cancelaram vs Não Cancelaram -->
<table>
  <tr>
    <td width="50%" valign="top">
      <h4>📊 Comparativo</h4>
      <table>
        <tr><th align="left">Métrica</th><th align="right">Não Cancelaram</th><th align="right">Cancelaram</th><th align="right">Diferença</th></tr>
        <tr><td align="left">Tempo de casa</td><td align="right">38 meses</td><td align="right">18 meses</td><td align="right">-20 meses</td></tr>
        <tr><td align="left">Gasto mensal</td><td align="right">R$ 61,27</td><td align="right">R$ 74,44</td><td align="right">+R$ 13,18</td></tr>
        <tr><td align="left">Gasto total</td><td align="right">R$ 2.549</td><td align="right">R$ 1.531</td><td align="right">-R$ 1.018</td></tr>
      </table>
    </td>
    <td width="50%" valign="top" align="center">
      <h4>🍕 Gráfico</h4>
      <pre style="font-size: 16px;">
Tempo de casa:   ████████████████████████████████████████░░░░░░░░ 38 x 18
Gasto mensal:    ██████████████████████████████████████████████████ R$61 x R$74
      </pre>
    </td>
  </tr>
</table>

<!-- Churn por Tipo de Contrato -->
<table>
  <tr>
    <td width="50%" valign="top">
      <h4>📊 Churn por Contrato</h4>
      <table>
        <tr><th align="left">Contrato</th><th align="right">Cancelamento</th></tr>
        <tr><td align="left">Mensal</td><td align="right">42%</td></tr>
        <tr><td align="left">Anual</td><td align="right">11%</td></tr>
        <tr><td align="left">Bianual</td><td align="right">3%</td></tr>
      </table>
    </td>
    <td width="50%" valign="top" align="center">
      <h4>🍕 Gráfico Pizza</h4>
      <pre style="font-size: 16px;">
Mensal:  ████████████████████████████████████████░░░░░░░░░░░░░░░░░░ 42%
Anual:   ███████████░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░ 11%
Bianual: ███░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░ 3%
      </pre>
    </td>
  </tr>
</table>

<!-- Churn por Forma de Pagamento -->
<table>
  <tr>
    <td width="50%" valign="top">
      <h4>📊 Churn por Pagamento</h4>
      <table>
        <tr><th align="left">Pagamento</th><th align="right">Cancelamento</th></tr>
        <tr><td align="left">Cheque eletrônico</td><td align="right">45%</td></tr>
        <tr><td align="left">Cheque físico</td><td align="right">19%</td></tr>
        <tr><td align="left">Transferência</td><td align="right">17%</td></tr>
        <tr><td align="left">Cartão de crédito</td><td align="right">16%</td></tr>
      </table>
    </td>
    <td width="50%" valign="top" align="center">
      <h4>🍕 Gráfico Pizza</h4>
      <pre style="font-size: 16px;">
Cheque eletrônico: ████████████████████████████████████████████████████░░ 45%
Cheque físico:     ████████████████████░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░ 19%
Transferência:     █████████████████░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░ 17%
Cartão de crédito: ████████████████░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░ 16%
      </pre>
    </td>
  </tr>
</table>

<!-- Churn por Tipo de Internet -->
<table>
  <tr>
    <td width="50%" valign="top">
      <h4>📊 Churn por Internet</h4>
      <table>
        <tr><th align="left">Internet</th><th align="right">Cancelamento</th></tr>
        <tr><td align="left">Fibra óptica</td><td align="right">41%</td></tr>
        <tr><td align="left">DSL</td><td align="right">19%</td></tr>
        <tr><td align="left">Sem internet</td><td align="right">7%</td></tr>
      </table>
    </td>
    <td width="50%" valign="top" align="center">
      <h4>🍕 Gráfico Pizza</h4>
      <pre style="font-size: 16px;">
Fibra óptica: ████████████████████████████████████████░░░░░░░░░░░░░░░░ 41%
DSL:          ████████████████████░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░ 19%
Sem internet: ███████░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░ 7%
      </pre>
    </td>
  </tr>
</table>

## 👩‍💻 Autora

Aluna: 
**Janaina Cardoso**  




<!-- Fim do README -->
