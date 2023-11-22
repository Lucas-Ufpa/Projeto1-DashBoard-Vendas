#Processo de BI(Business Intelligence)<h1>

1) Trazer dados de algum lugar (execel, BD, etc);

2) Tratar esse dados
  
3) Relacionamento entre tabelas
   juntas informações de varias tabelas em apeans uma tabela para ter a visualização desses dados cruzados.
4) Criar fórmulas/ analises

5) Criar o seu relatório/Dashboard

6) Compartilhar o seu relatório/Dashdoard

#Power BI x Power Query (dentro do BI para Editar planilhas)<h1>

Limite de linhas do excel: 1.048.576 linhas, o 	BI não tem limites de linhas

Fez alguma coisa e quer voltar atrás (crtl z não funciona, etapas aplicadas) por que é melhor que o ctrl Z ?

Podemos multiplicar o valor da coluna "PrecoUnitario" e "Qtd.Vendida" para termos uma receita(faturamento)
(selecionar ambas e criar nova coluna: faturamento)

Essas edições, onde é melhor para fazer no excel ou no power query ? - A principal é a automação (pagina inicial - atualizar visualização)

- nome cliente (inverter posição) - varinha magica (adicionar coluna - coluna de exemplos)

PARA APRESENTAR OS DADOS VAMOS USAR O METODOS TOP-DOWN - informações mais genericas e depois mais detalhes;

-cartão

extensão do PowerBI - pbix

1 - QUAL O PRODURTO MAIS VENDIDO ?

Para fazer top 5 usar cartão de linha multipla

2 -QUAL O FATURAMENTO TOTAL ?

3 - TOTAL DE FATURAMENTO DE CADA UMA DAS MARCAS(marca x faturamento)
Crescendo, diminuindo, sazonalidade ?
graficos CRESCENDO na VERTICAL (GRAFICO DE BARRAS EMPILHADAS)
quando é ranking graficos da vertical

Eixo X - números (FATURAMENTO)
Eixo Y - (MARCAS)

- Titulo : Faturamento por marca

PARA MELHORAR A VISUALIZAÇÃO (VISUAL / desmarcar o eixo e X / habilitar o rÓtulo de dados)

obs(grafico de pizza so quando forem poucas informações)

ITERATIVIDADE

- QUEREMOS MOSTRAR DUAS INFORMAÇÕES (G. COMBINADO) 
4 - QUAL (FATURAMENTO) A EVOLUÇÃO AO LONGO DO TEMPO ? (GRAFICO DE COLUNAS EMPILHADAS EM LINHAS) (faturamento e quant vendida por ano e por mes)
graficos CRESCENDO na horizotal
eixo Y COLUNA - Faturamento (vendas)
eixo X - data venda (ano e mes)

MAS COMO QUEREMOS MOSTRAS TBM O NUMERO DE VENDAS AO LONGO DO TEMPO 

- NO EIXO Y da linha : quantidade vendida

ALTERAR AS CONFIGS (ITERAÇÃO DO Pbi) - Arquivo/opções e configurações/configurações do relatorio/opções visuais(marcar a ultima opção)

5 -QUAL O DESEMPENHO DAS EMPRESAS EM CADA CONTINENTE? (faturamento por continente)
localização : continente
tamanho da bolha : faturamento
