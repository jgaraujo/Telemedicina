# Fundamentos em Informática Médica e Telemedicina - Curso de Ciência da Computação - UFAL

Análise de segmentos de imagens medicas e extração de atríbutos.

###Professor
 * Prof. Dr. Marcelo Costa Oliveira  <mcoliveira@ic.ufal.br>

###Alunos
*Andre Moabson
*Carla Mylena
*Jonatas Gonzaga
	
	
Descrição da atividade

1 - Obter o nódulo de câncer pulmonar segmentado  
     *https://dl.dropboxusercontent.com/u/11507361/noduloSegmentado.tar)

2 - Utilizar FIJI (https://fiji.sc/) para processar as imagens.
     *Foi utilizado um plugin pré-instalado chamado Trainable Weka Segmentation

3 - Executar o software FIJI, e importar o segmento de imagem em que se deseja extrair atributos.
	 *Para este caso, foi utilizado o seguimento 19.
	
	Passo: File -> Import -> Image 
	           Type - > 8-bit

4 - Fazer uso do plugin Trainable Weka Segmentation.
	 Plugin -> Segmentation -> Trainable Weka Segmentation

5 - Demarcar trecho da imagem a ser processada e adicionar classe  e posteriormente salvar os dados.

6 - Abrir o Weka Explorer atraves do botão ilustrado por um passáro na mesma janela.

7 - No Weka Explorer deve-se marcar atributos desejados e acionar visualização dos mesmos.

obs.: O arquivo com as extrações foi nomeado de "data.arff". Explorando tal arquivo é possível analisar todas os atributos.
		O arquivo "fig1.png"


