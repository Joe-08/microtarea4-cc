# microtarea4-cc
Microtarea 4 de Cloud Computing

## Dataset de pruebas

![Imagen 1](img1.jpeg)

## Escalabilidad Vertical

Para poder aumentar o disminuir la cantidad de pods utilizando StatefulSet se hace con el siguiente comando:

```
kubectl scale --replicas=4 statefulset/cassandra
```
![Imagen 2](img2.jpeg)

## Escalabilidad Horizontal

Para aumentar o disminuir la cantidad de nodos utilizando k8ssandra es:
```
```

## Conclusiones

Cassandra es una base de datos escalable que nos permite separar la información a través de keys especificados por el usuario
