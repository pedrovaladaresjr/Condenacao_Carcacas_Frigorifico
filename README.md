# Condenacao_Carcacas_Frigorifico


### Descrição dos Dados

O objetivo é analisar os dados referentes aos abates realizados com base nas informações.
O conjunto de dados é composto por informações detalhadas no arquivo **_Base_de_dados_Seleção_01.2024_** dentro da pasta **_Dados_**.

O conjunto de dados possui as seguintes variáveis:  

 • **Dia_Abate:** Dia em que o lote de animais foi abatido no estabelecimento.  
 • **Mes_Abate:** Mês em que o lote de animais foi abatido.  
 • **Ano_Abate:** Ano em que o lote de animais foi abatido.  
 • **Data_Abate:** Data completa do abate do lote.  
 • **Lote:** Número de identificação do lote de animais abatido.  
 • **Especie:** Espécie abatida no estabelecimento (apenas "Ave").  
 • **Diagnostico:** Descrição das alterações visíveis observadas nas carcaças.  
 • **Parte_Afetada:** Parte do animal afetada por alterações visíveis.  
 • **Qtd_Parte:** Quantidade de partes afetadas no lote abatido.  
 • **Destino:** Decisão sobre a destinação das partes afetadas no lote abatido no dia. 


 ### Distribuição Temporal dos Abates    
 
   • Analisaremos a distribuição dos abates ao longo do tempo, considerando as variáveis DiaAbate, MesAbate, e AnoAbate. Será verificado se há sazonalidade nos dados, ou 
      seja, padrões de variação ao longo dos meses ou anos.  
      
   • Gráfico de linha mostrando a evolução da quantidade de abates por mês e ano.  
        
### Diagnósticos e Partes Afectadas

   • A variável Diagnóstico detalha as alterações nas carcaças. Realizaremos uma análise de frequências para identificar os diagnósticos mais comuns.  
   • Tabela de frequências para Diagnósticos e Parte Afetada.
   • Gráfico de barras para visualização dos diagnósticos mais frequentes.  
   
### Quantidade de Partes Afetadas  

   • A coluna **_Qtd_Parte_** será analisada para entender a distribuição da quantidade de partes afetadas em cada lote. 
   • Boxplot para visualizar a dispersão e a presença de outliers. 
   • Média e mediana da quantidade de partes afetadas. 
   
### Destino das Partes Afetadas  

   • O destino das partes afetadas será analisado, relacionando com os diagnósticos.  
   • Tabela de contingência entre Diagnóstico e Destino.  
   • Gráfico de barras mostrando a proporção de partes descartadas versus aprovadas.  

### Análise de Outliers  

   • Analisaremos se há outliers nas variáveis quantitativas, como **_Qtd_Parte_**, e investigaremos se esses valores atípicos afetam a análise.  
   •Identificação de outliers nas variáveis numéricas.  
