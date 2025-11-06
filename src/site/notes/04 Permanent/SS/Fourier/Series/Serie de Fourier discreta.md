---
{"dg-publish":true,"permalink":"/04-permanent/ss/fourier/series/serie-de-fourier-discreta/"}
---

Es la versión discreta de la serie de Fourier que se aplica a secuencias periódicas en lugar de señales continuas. Si se tiene una señal discreta y periódica $x[n]$ con período $N$, esta señal puede ser expresada como una combinación de exponenciales complejas (o sinusoide) de frecuencias distintas 
$$
x[n] = \sum_{k=0}^{N-1}{C_k e^{\frac{i2\pi kn}{N}}}
$$
Donde:
- $C_k$ son los coeficientes de la serie de Fourier discreta, que representan la cantidad de energía en la frecuencia k.
- $N$ es el periodo de la señal.
- $e^{\frac{-i2\pi kn}{N}}$ representa una onda compleja en la frecuencia discreta k.
# Relaciones 
[[04 Permanent/SS/Fourier/Series/Coeficientes de la serie de Fourier Discreta\|Coeficientes de la serie de Fourier Discreta]]
[[04 Permanent/SS/Fourier/Series/Serie de Fourier\|Serie de Fourier]]
