# Criar etiqueta de preço usando Pyhton
Neste projeto desenvolvi um programa com interface gráfica para criar etiquetas de preços personalizadas usando um layout em PowerPoint.
O programa irá fazer a leitura dos dados em uma planilha Google que foi publicada na Web, nessa planilha contém as informações sobre os produtos como: Descrição, preço, características, etc.
Os dados são carregados da planilha em um dataframe, depois o arquivo .pptx do layout é carregado. O pragrama identifica a quantidade de produtos na planilha e cria um slide para cada um, após isso ele vai preencher para caixa de texto no slide com os dados da planilha. Após finalizar ele salva uma cópia desse arquivo em PowerPoint com todas as alterações que estará disponível para o usuário.

No script criei uma função para cada layout de etiquetas e uma interface gráfica onde o usuário seleciona qual modelo de etiqueta deseja e clica no botão "Gerar". Fazendo isso o programa identifica quais layouts de etiquetas o usuário escolheu e chama a função correspondente para gerar as etiquetas.
