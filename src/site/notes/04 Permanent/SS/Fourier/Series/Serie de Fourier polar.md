---
{"dg-publish":true,"permalink":"/04-permanent/ss/fourier/series/serie-de-fourier-polar/"}
---

Si la señal periódica $g(t)$ es real, entonces los coeficientes trigonométricos de la serie de Fourier ($a_0$, $a_n$ y $b_n$) también son reales.
 En consecuencia, la serie de Fourier trigonométrica contiene términos de seno y coseno con valores reales de la misma frecuencia. Podemos combinar los 2 términos en un solo término de la misma frecuencia usando la conocida identidad trigonométrica de
 $$
 a_ncos(n2\pi f_0) + b_nsin(n2\pi f_0 t) = C_n cos(n\pi f_0+ \theta_n)
 $$
 Donde:
 $$
 C_n = \sqrt{{a_n}^2 + {b_n}^2} 
 $$
 $$
 \theta_n = tan^{-1}(\frac{-b_n}{a_n})
 $$
 Por tanto la serie de Fourier en su forma trigonométrica **compacta** está dada por:
 $$
 g(t) = C_0 + \sum_{n=1}^{\infty}{C_ncos(n2\pi f_0 t + \theta_n)}
 $$

# Relaciones 
[[04 Permanent/SS/Fourier/Series/Serie de Fourier\|Serie de Fourier]]


 
 