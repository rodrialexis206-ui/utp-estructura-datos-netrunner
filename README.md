# Netrunner — Simulador de Propagación de Malware en Java

Laboratorio académico de **Estructura de Datos** (Licenciatura en Ciberseguridad — Universidad Tecnológica de Panamá, FISC) enfocado en modelar la propagación de amenazas en redes mediante estructuras de grafos en Java[cite: 1, 2, 12].

## 1. Propósito del Laboratorio
Simular cómo se propaga un malware a través de una red de nodos interconectados utilizando un **grafo no dirigido y ponderado** implementado con **lista de adyacencia**, analizando rutas, costos/pesos de enlace y recorridos de propagación con fines académicos y de seguridad defensiva.

## 2. Topología y Estructura de Datos
* **Modelo de red:** Grafo no dirigido y ponderado donde cada vértice representa un host/nodo y cada arista representa una conexión bidireccional con un peso asociado[cite: 12].
* **Representación:** Lista de adyacencia implementada en Java para gestionar vecinos y pesos de forma eficiente[cite: 12].
* **Recorridos y análisis:** Exploración de nodos alcanzables y rutas de propagación (BFS/DFS) y manejo de datos de entrada/salida.

## 3. Procedimiento y Ejecución
1. Clonar o abrir el repositorio en tu entorno de desarrollo con soporte para **Java** (por ejemplo, VS Code o IntelliJ IDEA)[cite: 2, 12].
2. Compilar las clases del proyecto y ejecutar la clase principal (`Main`).
3. Cargar o definir la topología del grafo (nodos, conexiones y pesos) e iniciar la simulación desde el nodo origen.
4. Observar el comportamiento de propagación y los resultados generados en consola o interfaz.

## 4. Licencia
Este proyecto se distribuye bajo la **Licencia MIT**; consulta el archivo `LICENSE` para más detalles[cite: 2, 12].
