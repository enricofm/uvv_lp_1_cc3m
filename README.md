# PSET1
Aluno: Enrico Freitas Modena - CC3M  
Professor: Abrantes Araujo Silva Filho
## Questões
**Questão 01:**  
O resultado esperado seria uma imagem de mesma altura (1 pixel) e largura (4 pixels),  
com pixels: [226,166,119,55]. A inversão é calculada subtraindo o valor “cor”, de cada  
pixel, de 255, o valor máximo de cor que um pixel pode assumir - nesse caso, a cor branca.

**Questão 02:**  
![alt text](https://github.com/enricofm/uvv_lp_1_cc3m/blob/main/bluegill_invertido.png)
bluegill_invertido.png

**Questão 03:**  
Kernel: [0.00 -0.07 0.00, -0.45 1.20 -0.25, 0.00 -0.12 0.00]  
Imagem de amostra: [80 53 99, 129 127 148, 175 174 193]  

Multiplicando um pelo outro = [ 0.00 -3.71 0.00, -58.05  152.4  -37, 0.00 -20.88 0.00]

Combinação linear = 152.4 - 3.71 - 37 - 58.05 - 20.88 = 32.76

**Questão 04:**  
![alt text](https://github.com/enricofm/uvv_lp_1_cc3m/blob/main/pigbird_kernel.png)
pigbird_kernel.png  

**Questão 05:**  
![alt text](https://github.com/enricofm/uvv_lp_1_cc3m/blob/main/cat_blur05.png)
cat_blur05.png  

![alt text](https://github.com/enricofm/uvv_lp_1_cc3m/blob/main/python_focada.png)
python_focada.png

**Questão 06:**  
O kernel Kx quando aplicado na imagem, destaca as bordas horizontais.  
Já o kernel Ky destaca as bordas verticais. Ambos são utilizados  
para calcular as aproximações das derivadas da imagem, e quando aplicados  
juntos, formam o seguinte efeito:

![alt text](https://github.com/enricofm/uvv_lp_1_cc3m/blob/main/construct_bordas.png)
construct_bordas.png
