<div align="center">
    <h1>Sysvision - Data Analytics com Power BI</h1>
</div>
<br><br>

<div align="center">
    <img align="center" src="assets\images\dio-logo.png" alt="Logo DIO" width="" height="60" hspace="80">
    <img align="center" src="assets\images\sysvision-logo-darkmode.png" alt="Logo Sysvision" width="" height="60" hspace="">               
</div>
<br><br>

<div align="center"><img src="assets\images\bootcamp-logo.png" alt="Logo bootcamp" width="" height="300" hspace="">
</div>
<br><br>

<div align="center">
    <img src="assets\images\bootcamp-dio.png" alt="Bootcamp DIO" width="300" height="" hspace="10">
</div>     
<br><br>

<div align="center">                           
    <img align="center" src="assets/images/power-bi.png" alt="Power Bi" height="50" hspace="10">
    <img align="center" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/azuresqldatabase/azuresqldatabase-original.svg" alt="SQL Database" height="50" hspace="10">    
    <img align="center" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/mysql/mysql-original-wordmark.svg" alt="MySQL" height="80">                
</div>
<br><br>

<div align="center">
    <img src="https://img.shields.io/badge/IN%C3%8DCIO-30%2F07%2F2024-green" hspace="5">
    <img src="https://img.shields.io/badge/T%C3%89RMINO-22%2F09%2F2024-red" hspace="5">
    
</div>
<br>
<hr>
<div align="center">
<h3>82 horas | 28 cursos | 9 desafios de projeto | 4 desafios de código | 1 lives</h3>
</div>
<hr>

## Introdução
Olá,

Esse repositório corresponde ao projeto "Modelando um Dashboard de E-commerce com Power BI Utilizando Fórmulas DAX" da [DIO - Digital Innovation One](https://www.dio.me/).
<hr>

## Objetivo

Neste poojeto, aplica-se as técnicas de transformação de dados com Power BI. 

Para algumas etapas pode ser preciso utilizar DAX. 

Utilizada a tabela única de Financial Sample para criar as tabelas dimensão e fato do nosso modelo baseado em star schema.

O processo consiste na criação das tabelas com base na tabela original. A partir da cópia serão selecionadas as colunas que irão compor a visão da nova tabela. Sendo assim, a partir da tabela principal serão criadas as tabelas:

- Financials_origem (modo oculto – backup)

- D_Produtos (ID_produto, Produto, Média de Unidades Vendidas, Médias do valor de vendas, Mediana do valor de vendas, Valor máximo de Venda, Valor mínimo de Venda)
- D_Produtos_Detalhes(ID_produtos, Discount Band, Sale Price,  Units Sold, Manufactoring Price)
- D_Descontos (ID_produto, Discount, Discount Band)
- D_Detalhes (*)
- D_Calendário – Criada por DAX com calendar()
- F_Vendas (SK_ID , ID_Produto, Produto, Units Sold, Sales Price, Discount  Band, Segment, Country, Salers, Profit, Date (campos))

Reorganição das colunas.
  
Explorado todos os conceitos que aprendemos nessa imersão e replicado este projeto prático. 
<br>
<hr>

## Próximos passos

Continuar o evoluindo no estudo com Power BI para futuros projetos e aplicações. 
<hr>

## Tecnologias Utilizadas

<div align=left>
    <img align=center src="assets/images/power-bi.png" alt="Power Bi" width="" height="60" hspace="5"/>
</div>

## Cursos Envolvidos
### **Sysvision - Data Analytics com Power BI** 
#### **Modelagem de Dados com Power BI:**
- Modelando um Dashboard de E-commerce com Power BI Utilizando Fórmulas DAX.
<hr>

## Repositório Original do GitHub
Referência direta ao código-fonte original.

- Juliana Mascarenhas: [Juliana Mascarenhas](https://www.linkedin.com/in/juliana-mascarenhas-ds/)
- Endereço: [power_bi_analyst](https://github.com/julianazanelatto/power_bi_analyst)
<hr>

## Agradecimentos
Gostaria de agradecer a [Sysvision](https://www.sysvision.global/) e a [DIO - Digital Innovation One](https://www.dio.me/) pela oportunidade e a instrutora [Juliana Mascarenhas](https://www.linkedin.com/in/juliana-mascarenhas-ds/) por compartilhar seu conhecimento.
