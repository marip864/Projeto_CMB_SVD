# 🌌 Separação da Radiação Cósmica de Fundo com SVD

Este repositório explora a aplicação da Decomposição em Valores Singulares (SVD) como ferramenta matemática para separar a radiação cósmica de fundo (CMB) de outros sinais presentes em dados astrofísicos disponibilizados pela NASA. A proposta é investigar como técnicas de álgebra linear podem auxiliar na análise de grandes volumes de dados cosmológicos, contribuindo para o entendimento da estrutura do universo primitivo.

## Objetivo

Utilizar a SVD para identificar e isolar componentes relevantes da CMB em conjuntos de dados reais, avaliando a eficácia da técnica na remoção de ruído e na separação de fontes mistas, como radiação galáctica e instrumental.

## Motivação

A radiação cósmica de fundo é uma das principais evidências do modelo do Big Bang. No entanto, os dados capturados por satélites contêm interferências de diversas fontes; logo, métodos como a SVD permitem decompor os dados em componentes ortogonais, facilitando a distinção entre sinal e ruído.

## Metodologia

1. **Aquisição dos dados**: Utilização de mapas de temperatura da CMB disponibilizados pela NASA.
2. **Pré-processamento**: Normalização, remoção de artefatos e preparação dos dados para análise.
3. **Aplicação da SVD**: Decomposição dos dados em componentes singulares.
4. **Análise dos componentes**: Identificação dos modos dominantes associados à CMB.
5. **Visualização**: Geração de gráficos para interpretação dos resultados.

## Resultados obtidos

- Separação clara entre componentes galácticos e cosmológicos.
- Redução significativa de ruído instrumental.
- Visualizações dos modos singulares mais relevantes.

## Requisitos

- Python 3.8+
- NumPy
- Scikit-Learn
- Matplotlib

## Referências

GOLUB, G. H.; VAN LOAN, C. F. Matrix Computations. 3. ed. Johns Hopkins University Press, 1996. Disponível em: <https://pages.stat.wisc.edu/~bwu62/771/golub1996.pdf>. Acesso em: 17 jul. 2025. 

ANTON, H.; RORRES, C. Álgebra linear com aplicações. 10. ed. Porto Alegre: Bookman, 2012.  

LEON, S. J. Algebra linerar com aplicações. 8 ed. Rio de Janeiro: LTC, 2013. 

STEINBRUCH, A.; WINTERLE, P. Álgebra linear. 2. ed. Rio Grande do Sul: Pearson, 1995.  

MOUNIKA, K.; LAKSHMI, D. S. N.; ALEKYA, K. SVD based image compression. International Journal of Engineering Research and General Science, v. 3, n. 2, p. 1271–1278, 2015.  

BRESSAN, G. M.; SANTOS, J. F. dos; MARTINEZ, A. L. M. Aplicação da Decomposição em Valores Singulares para compressão de imagens. C.Q.D. - Revista Eletrônica Paulista de Matemática, v. 22, n. IC, p. 96–109, jul. 2022. 

DELABROUILLE, J. et al. Blind component separation for CMB observations: comparison of methods. Monthly Notices of the Royal Astronomical Society, v. 346, p. 1089–1102, 2003.‌ 

## 👩‍🔬 Autoria

Este projeto é parte de uma iniciativa educacional para explorar aplicações de matemática e ciência de dados em astrofísica, desenvolvido por Bruna Guedes Pereira e Mariana Melo Pereira, alunas da Ilum Escola de Ciência.
