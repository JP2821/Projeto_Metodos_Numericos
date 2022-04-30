# Projeto_Metodos_Numericos
Integrantes : 
### João Pedro Ribeiro da Silva Dias - jprsd
### Rodrigo Santos Batista - rsb6
### Vinícius Sales Oliveira - vso2
### Yasmin Maria Wanderley Soares - ymws

# Objetivos
Tendo em vista o cenário atual em que há muita resistencia à vacina por uma parcela da população e por setores expecíficos do governo, ainda que comprovada sua eficiência e eficácia.Dito isto iremos aqui tentaremos implementar um preditor de casos de covid e iremos aqui estabelecer um contraste, projetanto um cenário no qual a existência dela é quase nula ou nenhuma. Dessa maneira, será observada a progressão da doença ao longo do tempo e uma análise em cima do gráfico será efetuada para fins de comparação, caso dispuséssimos de uma maior taxa de vacinação.

# Bibliotecas utilizadas
## scipy.integrate import odeint
Necessária para a resolução das EDO's as quais utilizaremos para tentar prever os casos de covid.
## numpy
Utilizamos está biblioteca para a criação de arrays os quais serão uteis em nossa EDO.
## plotly.graph_objects
Biblioteca utilizada para tornar possiveis as iterações gráficas e plotes de gráficos necessários.

# Como usar os gráficos iterativos
No canto superior direito da janela onde o gráfico está plotado haverá o seguinte menu:

![iteração_gráfica_1](https://user-images.githubusercontent.com/78371415/166106807-c1ac06a4-5608-443e-a09b-4746b3193094.png)

## Dowload plot as png
Permite,caso se deseje ou seja necessário,que seja feito o download do gráfico plotado em formato de png.

![iteração_gráfica_0](https://user-images.githubusercontent.com/78371415/166106980-8fe9d340-a2d2-4297-a382-09d0d18e4c83.png)

## Zoom
Permite que uma parte do gráfico seja selecionada e ampliada,caso se deseje voltar para o tamanho original,basta efetuar dois cliques seguidos.

![iteração_gráfica_2](https://user-images.githubusercontent.com/78371415/166107184-a65d5d1f-c063-4cf5-93ec-123b57ad52f5.png)

![ezgif com-gif-maker (1)](https://user-images.githubusercontent.com/78371415/166107718-9aca9b42-056f-49d3-9f0f-b0d242e31b4d.gif)

### Zoom In e Zoom Out
Caso queira ampliar todo o gráfico essas duas opções permitem aumentar(Zoom In) ou diminuir(Zoom Out).

![iteração_gráfica_3](https://user-images.githubusercontent.com/78371415/166107961-306ad192-12aa-438b-832d-ac976bfe902f.png)

![iteração_gráfica_4](https://user-images.githubusercontent.com/78371415/166108011-da898a26-1de1-4149-844a-40e0571a86e1.png)

![ZoomIn_ZoomOut](https://user-images.githubusercontent.com/78371415/166108038-e2bd879f-293f-4f42-ba66-f35108e636d5.gif)

## Pan
Permite manipular a imagem gráfica e move-la de acordo com a necessidade.

![iteração_gráfica_6](https://user-images.githubusercontent.com/78371415/166108576-df70ae39-7888-4e0d-a210-66c86e2830d4.png)

![Pan](https://user-images.githubusercontent.com/78371415/166108655-ae15cd27-644b-4901-949a-736c9d118ded.gif)

## Autoscale
Restaura o plot gráfico para o tamanho original.

![iteração_gráfica_5](https://user-images.githubusercontent.com/78371415/166108241-b0f3a459-be67-48f2-aac3-9f2a4d1cc395.png)

![auto_scale](https://user-images.githubusercontent.com/78371415/166108450-ab198708-48d5-4f96-be89-e9ab8a4bb1ce.gif)



