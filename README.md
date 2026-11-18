# EQUIPO-3

Integrantes:

-Guerrero Martinez Enrique Rafael.

-Hernandez Olaya Luis Eduardo .

-Hurtado Cervantes Samuel.

Integrales triples en coordenadas esféricas

Volumen del sólido dentro de una esfera y arriba de un cono.

Problema:

Calcular el volumen del sólido limitado por la esfera

$$x^2 + y^2 + z^2 = 4$$

y que está arriba del cono

$$z = \sqrt{x^2 + y^2}$$

Metodología
1. Análisis geométrico: esfera de radio 2 y cono con vértice en el origen; ambos tienen simetría de revolución alrededor del eje z.

2. Intersección: al sustituir el cono en la esfera se obtiene z = √2 y ρ = 2.
   
3. Sistema de coordenadas: esféricas, porque todos los límites quedan constantes.

4. Transformación:

x = ρ sen φ cos θ, y = ρ sen φ sen θ, z = ρ cos φ

Jacobiano: dV = ρ² sen φ dρ dφ dθ

5. Límites: 0 ≤ ρ ≤ 2, 0 ≤ φ ≤ π/4, 0 ≤ θ ≤ 2π

6. Integral:
   
$$V = \int_0^{2\pi}\int_0^{\pi/4}\int_0^{2} \rho^2 \sin\varphi \, d\rho \, d\varphi \, d\theta$$

7. Simulación y verificación en MATLAB con integral3.
