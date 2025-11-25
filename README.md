Cómo ejecutar el proyecto en Google Colab
Estas instrucciones permiten entrenar e inferir la CNN del proyecto NeuroBot usando la estructura de carpetas almacenadas en Google Drive.

1. Subir la carpeta completa NeuroBot a Google Drive
2. Abrir Google Colab
3. Montar Google Drive
   Ejecutar la celda:
   <img width="857" height="210" alt="image" src="https://github.com/user-attachments/assets/f3b6dd86-9748-4bde-aef4-6c92d7b31e5b" />
Aceptar permisos.
4. Verificar rutas dentro del notebook
<img width="1295" height="226" alt="image" src="https://github.com/user-attachments/assets/7ef9c6bf-42f2-49e0-8b0a-805ee158ee74" />
5. Ejecutar el split del dataset (automático)
6. Ejecutar el entrenamiento
En el notebook “Entrenamiento” correr todas las celdas en orden:

+Librerías
+Montar Drive
+Cargar dataset
+Crear split
+DataLoaders
+Definir la CNN
+Entrenamiento
+Gráficas

Guardar modelo + configuraciones

Al finalizar, tendrás generado:

<img width="225" height="140" alt="image" src="https://github.com/user-attachments/assets/d0042c02-3d71-4bde-af0b-1d45145eed2d" />

