---
{"dg-publish":true,"permalink":"/04-permanent/ss/fourier/series/serie-de-fourier-trigonometrica/"}
---

Sea una señal $g(t)$ una señal periódica. $g(t)$ puede ser representada exactamente por la suma infinita de funciones sinusoidales con distintas amplitudes y frecuencias múltiplo de la frecuencia de la señal $g(t)$.
$$
g(t)= a_0 + \sum_{n=1}^{\infty}{[a_ncos(2\pi n f_0 t) + b_n sin(2\pi nf_0t)]}
$$
Los términos $a_0$, $a_n$ y $b_n$ se calculan de la siguiente manera:
$$
a_0 = \frac{1}{T} \int_{\frac{-T}{2}}^{\frac{T}{2}}{g(t)dt}
$$

$$
a_n = \frac{2}{T} \int_{\frac{-T}{2}}^{\frac{T}{2}}{g(t)cos(2\pi\frac{1}{T}t)dt}
$$

$$
b_n = \frac{2}{T} \int_{\frac{-T}{2}}^{\frac{T}{2}}{g(t)sin(2\pi\frac{1}{T}t)dt}
$$

# Relaciones
[[04 Permanent/SS/Fourier/Series/Serie de Fourier\|Serie de Fourier]]
