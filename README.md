# Datascience
Repository of data science studies

## Comands for dataframe pandas

### Retira linha pelo index
'''
df.drop([ 0,1,2,3 ])
'''
### Filtra as linhas com os comandos logicos
filtro  = df['coluna'] > 1
### Cria novo dataframe sem o filtro
df_filtrado = df[filtro]
### Retira coluna pelo nome
df.drop(columns=['coluna'])
### Mostra a posição pelo numero do index e coluna
df.at[ numeroIndex, 'coluna' ]
	
### Filtra linha pela coluna e nome da posição
df[df['coluna'] == 'nomeposição']
### procura dentro do df pela coluna descrições
df.loc[df['coluna'].isin( ['nome1','nome2'])]
	
### Renomeia colunas
Df.columns = [‘nomecolu1’,’ ‘nomecolu2’]
### Agrupa e mostra valores iguais para a coluna especifica
df.groupby(['Coluna']).size()
### Localiza os nomes na coluna indicada e renomeia
df.loc[dft['Coluna'].isin( ['nome1','nome2']), 'Coluna'] = "Novonome"
### Localiza as linhas da coluna especifica pelo sinal
df.loc[df['Coluna'] >=  numero] 
	
### Mostra do maior para o menor com base na coluna indicada
df.sort_values('Coluna', ascending=True)
### Reseta o valor do index e exclui
df.reset_index(drop = True)
### Descreve informações do dataframe
df.describe	
### mostra tamanho do dataframe
df.shape	mostra tamanho do dataframe
### passa numero de colunas
len(df_dados_paises.columns)
### mostra quantidade de linhas
len(df_dados_paises)	mostra quantidade de linhas
