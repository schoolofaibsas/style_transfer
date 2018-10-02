# Style Transfer

## Objetivos

Lograr capturar la esencia (o "contenido") de una imagen, para luego ser re-pintada utilizando un "estilo" capturado de otra imagen (o pintura).

> NOTA: este ejercicio fue creado a partir del trabajo de Walid Ahmad. Pueden acceder al repo original:
> https://github.com/walid0925/AI_Artistry

## Requerimientos

Utilizar el contenedor Docker que hemos preparado o utilizar el entorno anaconda y ejecutar el siguiente comando:

```
pip install --ignore-installed --user -r requirements.txt
```

## Framework

Vamos a emplear el framework Keras para la ejecución del modelo.
Utilizaremos una red neuronal entrenada: VGG-16.

## Imagen Docker

Para simplificar el trabajo, hemos creado una imagen docker en Docker Hub. Para ejecutarla debemos seguir los siguientes pasos:

1. Descargar e instalar Docker
2. Ejecutar el siguiente comando desde Terminal o CMD: "docker pull farreg/schoolofaibsas"
3. Ejecutar: "docker image ls"
4. Reconocer la imagen que dice "farreg/schoolofaibsas" y obtener su IMAGE ID
5. Ejecutar: "docker run -it -p 8888:8888 XXXX", donde XXXX es el IMAGE ID.

A partir de aquí podrán seguir el Online Coding Session paso a paso.

## Ejemplos

![Alt text](./examples/cubist_cat.png?raw=true "Cubist Cat")
![Alt text](./examples/starry_hall.jpg?raw=true "Starry Hall")
