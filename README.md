# Projeto01_UFJF_SIFT_RANSAC
Repositório atendendo a tarefa do Mestrado UFJF em Ciência da Computação.

----


- Este repositório contém todos os dados e funções necessários para reproduzir os resultados da tarefa prática do Departamento de Ciência da Computação da UFJF
" Criação de imagem panorâmica utilizando algoritmos SIFT (Scale Invariant Feature Transform) e RANSAC (Random Sample Consenssus) "

- Imagens utilizadas " imagem1.jpg e imagem2.jpg ".

-----
Informações sobre a atividade:

- Left img size ( 397 * 529 )
- Right img size ( 397 * 529 )
- Step1 - Extract the keypoints and features by SIFT detector and descriptor...
- Step2 - Extract the match point with threshold (David Lowe’s ratio test)...
- The number of matching points: 106
- Step3 - Fit the best homography model with RANSAC algorithm...
- The Number of Maximum Inlier: 97
- Step4 - Warp image to create panoramic image...
