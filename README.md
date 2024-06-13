## Segmentação de imagens por crescimento de regiões em áreas de desmatamento: estudo de caso das regiões sul e centro do bioma amazônico do Peru

### 📋 Pré-requisitos

Ambiente de programação Python com as bibliotecas:

```
imutils, imagecodecs, tifffile, numpy, matplotlib, gdal, cv2, sklearn.metrics	
```

## ⚙️ Executando os testes

- O script da segmentação utiliza as seguintes imagens como teste: `<data\imagem_segment_south_mayo2024_v2>` como a imagem a ser segmentada e `<data\Bosque_No_Bosque_2022_south>` como a imagem de referência (ground truth).

- O script retorna o resultado da segmentação nos formatos geotiff e shp. 

- Para avaliação da segmentação, verificar os resultados da função IoU

## ✒️ Autores
- Luis E. Sales do Nascimento
- Mateus R. de Vasconcelos Miron
- Juan C. Guerra
- Fabio H. Sakaguchi
