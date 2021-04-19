# Observaciones Laboratorio No. 9

## Preguntas :page_facing_up:

**1. ¿Qué diferencia existe entre las alturas de los dos árboles (BST y RBT)?**

Mientras que la altura del BST es de 29, la altura del RBT es de 13. Esta disminución en la altura sugiere que el RBT presenta considerablemente un mejor balance en comparación del BST.

**2. ¿Por qué pasa esto?**

Esta diferencia en la altura del RBT en comparación con la altura del BST se presenta debido a que el RBT es un árbol de auto-balance, mientras que el BST no lo es. Esta propiedad le permite al RBT reorganizarse a medida que se agregan nodos para garantizar el balance del árbol. De este modo, el RBT garantiza siempre una complejidad linearítmica ```O(log n)``` en el peor de los casos para insertar, remover u obtener elementos.
