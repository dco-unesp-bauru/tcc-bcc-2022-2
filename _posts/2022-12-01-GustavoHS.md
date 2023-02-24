---
layout: posts
title:  "Paralelização da técnica de extração de pontos de interesse FOAGDD utilizando a arquitetura CUDA"
date:   2022-12-01 16:16:29 -0600
categories: trabalho
autornick: GustavoHS
autor: "Gustavo Henrique Stahl"
orientador: "Prof. Dr. Antonio Carlos Sementille"

---

Consoante com o desenvolvimento tecnológico atual que, cada vez mais,
solicita abordagens que conectem o meio analógico e digital de maneira interativa, ou seja, funcionando em tempo real, o presente trabalho busca auxiliar nesse cenário ao acelerar uma das técnicas de extração de pontos de interesse em imagem presente no estado da arte da categoria, uma vez que são densamente utilizadas em áreas como realidade aumentada, veículos autônomos, robôs de serviço, reconstrução 3D, e diversas outras que necessitam produzir resultados rápidos e frequentes. O método escolhido para o aperfeiçoamento é o extrator de cantos FOAGDD (First-order Anisotropic Gaussian Direction Derivative) e seu processo de otimização se sustentou na massiva paralelização possibilitada pela arquitetura CUDA (Compute Unified Device Architecture) da NVIDIA. Os resultados obtidos com a melhoria proposta se mostraram promissores. Primeiramente, a saída produzida pela implementação original do método e a paralelizada em CUDA se mostraram muito similares, após serem testadas e comparadas em um conjunto de 28 imagens. Por último, o código proposto trouxe um Speed-up no tempo de execução de aproximadamente 3190 (66,03 segundos → 20,70 milisegundos) em relação à implementação original do FOAGDD, utilizando como base uma imagem padronizada de resolução 512 × 512 pixels.
