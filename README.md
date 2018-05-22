Raytracer implementdo con OpenMP
=================================


Basado en:
[Código Original](https://github.com/bnaveenkr/raytracer)

---------------------------------------------------------------

Elaborado por:
* Esquivel Guillén Alejandra Gpe.
* Reyes Flores Karen Jaqueline

Requerimientos para la ejecución:
* gcc >= 5
* OpenMP
* ImageMagick

Compilado:
```
gcc raytracer.c -o raytracer -lm -fopenmp
./raytracer
```

El programa siempre genera un archivo ppm de salida y para visualizarlas
se requiere convertir a jpg o png o un visor
Para las imagenes:
```
convert output.ppm salida.jpg
```
