Implementação em Python para transformar uma imagem colorida para níveis de cinza e para binarizada (0 e 255)  
1.Carregamento da Imagem: A imagem original é carregada a partir de um caminho especificado.   
2.Conversão para Níveis de Cinza: A imagem colorida é convertida para níveis de cinza (tons entre 0 e 255) utilizando uma fórmula que considera a contribuição das cores RGB (vermelho, verde e azul).    
3.Binarização da Imagem: A imagem em níveis de cinza é transformada em uma imagem binária (preto e branco), com um limiar de intensidade (threshold) de 128. Pixels acima do limiar são transformados em branco (255), enquanto os abaixo são transformados em preto (0).   
4.Exibição das Imagens: As três versões da imagem (original, em níveis de cinza e binarizada) são exibidas no ambiente Colab utilizando arquivos temporários e comandos de exibição nativos.  
