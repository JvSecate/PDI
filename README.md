
# Processamento de imagens




## Seminário

 - [Detecção de Deep Fake](https://docs.google.com/presentation/d/1yvHgMuWBDrcD3XUuwg2gyPgiWpAavQO1C-LfvnSGSpo/edit?usp=sharing)


## Relatório

#### Introdução

O processamento de imagens envolve manipulação e análise de matrizes que representam imagens digitais, como a construção de padrões com valores específicos de intensidade (por exemplo, 0 para preto e 255 para branco).

#### Fundamentos Imagens

As operações ponto a ponto incluem cálculo do negativo da imagem, redução pela metade da intensidade dos pixels e inclusão de formas geométricas, como quadrados brancos nos cantos ou um quadrado preto no centro da imagem. Já as operações por vizinhança implementam filtros de média e mediana utilizando várias abordagens para cálculo local com kernels.

#### Transformações de intensidade
A esteganografia em imagens explora técnicas para ocultar informações, como mensagens, em imagens ou videos, utilizando o planos de bits.
Transformações como logarítmica, potência e equalização de histograma ajustam características visuais, aprimorando contraste e detalhamento

#### Filtragem Espacial
A filtragem espacial é uma técnica essencial no processamento de imagens, utilizada para melhorar ou modificar características específicas das imagens. A operação de convolução, central para essa abordagem, permite a aplicação de diferentes filtros (como média, bordas e suavização) através de uma interação entre a imagem e um kernel.

####  Desafio Stanford
A detecção de defeitos em imagens de placas é usada no controle de qualidade industrial, onde técnicas de subtração de fundo são usadas para identificar alterações entre imagens. Ao subtrair as duas imagens, pode-se evidenciar as diferenças, que são analisadas para detectar falhas.

####  Transformada de Fourier
A Transformada de Fourier revela as componentes de frequência que compõem a imagem, facilitando a análise de padrões periódicos e ruídos. Ao realizar a transformação de Fourier, é possível observar a distribuição de frequências de uma imagem, o que é útil em diversas áreas, como compressão de imagens e filtragem de ruídos.

####  Filtragem Frequência
A Transformada de Fourier permite analisar as frequências presentes em uma imagem, revelando padrões e estruturas que não são facilmente visíveis no domínio espacial. Ao aplicar transformações geométricas como rotação, translação e zoom, o comportamento das componentes de frequência é alterado, influenciando o espectro de Fourier da imagem.

#### Morfologia
A morfologia matemática é uma técnica focado na manipulação da forma dos objetos dentro de uma imagem. Operações como erosão e dilatação são usadas para modificar a estrutura dos objetos, enquanto a abertura e o fechamento ajudam a suavizar ou eliminar ruídos, dependendo do tipo de operação realizada. A erosão reduz o tamanho dos objetos, enquanto a dilatação os expande. A abertura, que combina erosão seguida de dilatação, é eficaz para remover ruídos pequenos, enquanto o fechamento, que inverte a ordem, é usado para preencher buracos ou lacunas em objetos.