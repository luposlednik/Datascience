# Datascience
Repository of data science studies

## Comands for dataframe pandas

### df.drop([ 0,1,2,3 ]) |	retira linha pelo index
### filtro  = df['coluna'] > 1 |	filtra as linhas com os comandos logicos
### df_filtrado = df[filtro] |	Cria novo dataframe sem o filtro
	
### df.drop(columns=['coluna'])	Retira coluna pelo nome
### df.at[ numeroIndex, 'coluna' ]	Mostra a posição pelo numero do index e coluna
	
### df[df['coluna'] == 'nomeposição']	Filtra linha pela coluna e nome da posição
### df.loc[df['coluna'].isin( ['nome1','nome2'])]	procura dentro do df pela coluna descrições
	
### Df.columns = [‘nomecolu1’,’ ‘nomecolu2’]	Renomeia colunas
### df.groupby(['Coluna']).size()	Agrupa e mostra valores iguais para a coluna especifica
### df.loc[dft['Coluna'].isin( ['nome1','nome2']), 'Coluna'] = "Novonome"	Localiza os nomes na coluna indicada e renomeia
### df.loc[df['Coluna'] >=  numero] 	Localiza as linhas da coluna especifica pelo sinal
	
### df.sort_values('Coluna', ascending=True)	Mostra do maior para o menor com base na coluna indicada
### df.reset_index(drop = True)	Reseta o valor do index e exclui a 
### df.describe	
### df.shape	mostra tamanho do dataframe
### len(df_dados_paises.columns)	passa numero de colunas
### len(df_dados_paises)	mostra quantidade de linhas
