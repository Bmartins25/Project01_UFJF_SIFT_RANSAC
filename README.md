# Projeto01_UFJF_SIFT_RANSAC
Repositório atendendo a tarefa do Mestrado UFJF em Ciência da Computação.

----


- Este repositório contém todos os dados e funções necessários para reproduzir os resultados da tarefa prática do Departamento de Ciência da Computação da UFJF
" Criação de imagem panorâmica utilizando algoritmos SIFT (Scale Invariant Feature Transform) e RANSAC (Random Sample Consenssus) "

- Imagens utilizadas " imagem1.jpg e imagem2.jpg ".

-----
Informações sobre a atividade:

- Left img size ( 397 * 529 ) - imagem1
- Right img size ( 397 * 529 ) - imagem2
- Step1 - Extract the keypoints and features by SIFT detector and descriptor...
- Step2 - Extract the match point with threshold (David Lowe’s ratio test)...
- Pontos verdes = inliers
- Pontos vermelhos = outliers
- The number of matching points: 106
- Step3 - Fit the best homography model with RANSAC algorithm...
- The Number of Maximum Inlier: 97
- Step4 - Warp image to create panoramic image...

------

![image](https://github.com/Bmartins25/Projeto01_UFJF_SIFT_RANSAC/assets/42076192/4c761ab0-c8fc-4293-9b3a-1b5792da1d8b)
