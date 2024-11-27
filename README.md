# Universidad de Guadalajara
## Centro Universitario de Ciencias Exactas e Ingenierías
### Ing. Biomédica
### Materia: Métodos biomédicos de IA
### Profesor: Daniel Farfán

## Caso Práctico 5 - GNN: Recomendación de Seguimientos en una Red Social de Música
### Integrantes del equipo:
- Héctor Manuel Godínez Lozano
- José de Jesús González Hernández
- Diana Romina Miranda Grijalva

Este proyecto está inspirado en la idea de utilizar Graph Neural Networks (GNN) para realizar recomendaciones de seguimiento en una red social de música. Nuestro objetivo es construir y entrenar una GNN para recomendar nuevos seguimientos basados en las conexiones existentes entre los usuarios.

## Objetivos
- **Construir un modelo GNN**: Definir y compilar un modelo GNN utilizando PyTorch Geometric.
- **Entrenar el modelo**: Utilizar conjuntos de datos de entrenamiento para entrenar el modelo.
- **Evaluar el rendimiento**: Evaluar el rendimiento del modelo durante el entrenamiento.
- **Hacer recomendaciones**: Utilizar el modelo entrenado para recomendar nuevos seguimientos entre los usuarios.
- **Visualizar resultados**: Visualizar las recomendaciones generadas por el modelo.

## Estructura del Proyecto
1. **Preparación del Entorno y los Datos**: Configuración del entorno y carga de los datos desde un archivo CSV generado en Excel.
2. **Definición del Modelo GNN**: Implementación de las clases para el modelo GNN.
3. **Entrenamiento del Modelo**: Configuración de los optimizadores, la función de pérdida y entrenamiento de la GNN utilizando un bucle de entrenamiento.
4. **Generación de Recomendaciones**: Utilización del modelo entrenado para crear y visualizar recomendaciones de seguimiento.
5. **Visualización de Resultados**: Visualización de las recomendaciones generadas por el modelo.

## Instalación
### Requisitos
- Python 3.6 o superior
- PyTorch
- torch-geometric
- pandas
- matplotlib
- networkx

### Instalación usando Conda
```bash
# Crear un nuevo entorno virtual
conda create -n gnn_env python=3.8

# Activar el entorno virtual
conda activate gnn_env

# Instalar las dependencias
conda install pytorch torchvision torchaudio cudatoolkit=11.3 -c pytorch
pip install torch-geometric
pip install pandas matplotlib networkx
```
### Uso
1. Preparar los datos: Asegúrate de que tu archivo CSV con los datos de la red social de música esté disponible.
2. Ejecutar el notebook: Abre y ejecuta el notebook GNN_MusicSocialMedia.ipynb para entrenar el modelo y generar recomendaciones.

### Notas
* La base de datos fue creada por el equipo utilizando Excel y luego importada al entorno de trabajo.
* El proyecto se centra en una red social de música, donde los usuarios pueden seguir a otros usuarios y guardar playlists.
