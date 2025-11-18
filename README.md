---

# **Tarea 3 – Gustavo Montoya**

A continuación se presentan los apartados **2 y 3** de la Tarea 3.

---

##  **Cómo ejecutar el programa — Apartado 2**

1. **Descargar el dataset de imágenes desde Kaggle**
    [Dataset “Cat and Dog”](https://www.kaggle.com/datasets/tongpython/cat-and-dog?resource=download)

2. **Crear la estructura de carpetas** a la altura del apartado 3:

```
apartado2/
└── data/
    ├── train/
    └── val/
```

3. **Copiar los datos:**

   * Los contenidos de `training_set` → `apartado2/data/train/`
   * Los contenidos de `test_set` → `apartado2/data/val/`

   Debe quedar algo como:

```
apartado2/data/val/cats/cat.4003.jpg
```

4. **Entrenamiento y predicción**

   * Primero ejecutar `train`
   * Luego ejecutar `predict`

   Ya deberías ver la predicción correcta sobre una imagen, por ejemplo:

```python
predecir("apartado2/data/val/cats/cat.4003.jpg")
```

5. **Bonus**
   Ejecutar **Grad-CAM** para visualizar qué regiones de la imagen utiliza el modelo para tomar sus decisiones.

---

##  **Cómo ejecutar el programa — Apartado 3**

Dentro de la carpeta:

```
gpt-trained/
```

se encuentra:

* El archivo del modelo entrenado para **GPT-Español** (Parte 2 del Apartado 3).
* El notebook **explicacion_mini_gpt_transformer.ipynb**, el cual explica paso a paso el funcionamiento del modelo GPT implementado.

---

