---
{"dg-publish":true,"permalink":"/04-permanent/ss/fourier/transformadas/transformada-de-fourier/"}
---

Se utiliza principalmente para señales que no son necesariamente [[04 Permanent/SS/Señales/Señales periódicas\|periódicas]]. La idea es determinar cuanto se parece una señal $g(t)$ a una sinusoide, evaluando la sinusoide en todas las frecuencias.
La transformada de Fourier (FT) de una forma de onda $g(t)$ es:
$$
G(f)=F[g(t)]= \int_{- \infty}^{\infty}{ g(t)e^{-2j \pi ft}dt}
$$
Mientras que la transformada inversa de Fourier viene dada por:
$$
g(t)=F^{-1}[G(f)]=\int_{- \infty}^{\infty}{g(te^{-j2 \pi ft}dt)}
$$
Debido a que $e^{-j2 \pi ft}$ es complejo, entonces $G(f)$ es una función compleja. Entonces en términos de un sistema de coordenadas polares, la transformada de Fourier $G(f)$ puede reescribirse como un par de funciones reales usando la magnitud y fase:
$$
G(f)= |G(f)|e^{j \theta (f)}
$$
Para saber si una función $g(t)$ es transformable, se usan las [[04 Permanent/SS/Fourier/Transformadas/Condiciones de Dirichlet\|Condiciones de Dirichlet]].
# Calculo de la transformada de Fourier
Existen varias formas de calcular la transformada:
1. [[04 Permanent/SS/Fourier/Transformadas/Integración directa\|Integración directa]]
2. [[04 Permanent/SS/Fourier/Transformadas/Tabla de transformadas de Fourier\|Tabla de transformadas de Fourier]]
3. [[04 Permanent/SS/Fourier/Transformadas/Transformada rapida de Fourier\|Transformada rapida de Fourier]]
4. [[04 Permanent/SS/Fourier/Transformadas/Propiedades de la transformada/Propiedades de la transformada de Fourier\|Propiedades de la transformada de Fourier]]
# Relaciones
[[04 Permanent/SS/Señales y sistemas\|Señales y sistemas]]
[[04 Permanent/SS/Fourier/Series/Serie de Fourier\|Serie de Fourier]]
[[04 Permanent/SS/Fourier/Transformadas/Condiciones de Dirichlet\|Condiciones de Dirichlet]]
[[04 Permanent/SS/Señales/Señales periódicas\|Señales periódicas]]