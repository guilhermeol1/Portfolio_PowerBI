# Portfolio Power BI 📊 📈
<img width="1584" height="396" alt="Capa do portfolio de Power BI (1)" src="https://github.com/user-attachments/assets/1aaf82b9-21e2-43f4-80b5-e82b0bbc8c9a" />

Bem vindo(a) ao meu portfolio de projetos em Power BI!  
Neste repositório estão armazenados todos os dashboards que criei durante o início da minha jornada de estudos com o Microsoft Power BI, com foco em ingressar na área de analista de BI como estagiário.  
Esse é um portfolio diversificado com dashboards para as seguintes áreas de negócio:
- Vendas/Comercial

## Projeto de Vendas

Esse é um projeto de Análise Comercial utilizando o Power BI, feito durante o minicurso de Power BI da Xperiun. A base de dados fictícia foi fornecida pelo curso e contém duas tabelas uma de Vendas e outra dos Produtos.  
São duas opções de dashboard - um de tema claro e outro de tema escuro - onde são feitas análises relacionando receita/custo/margem de lucro da empresa com outras informações da base de dados, como grupo e linha do produto, ano/mês e vendedores/supervisores(separados por hierarquia).  
Há apenas um relacionamento entre as tabelas(Código do produto - 1 para muitos).  
As colunas de dia, mês e ano foram mescladas e uma nova coluna de receita foi criada durante a transformação dos dados no Power Query, além de 3 medidas usando DAX para utilizar os valores de receita, custo e margem de lucro.  
A base de dados original exibia as seguintes colunas:  
Tabela de Vendas: Dia/Mês/Ano/Nota Fiscal/cdProduto/cdVendedor/Vendedor/Supervisor/Quantidade/Valor Unitário/Receita -> Total de dados(originalmente): 549054  
Tabela de Produtos: Cod Produto/Grupo Produto/Linha Produto/Fornecedor/CustoUnitario -> Total de dados: 3335
