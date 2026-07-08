# ⚽ Predicción Bayesiana del Mundial FIFA 2026

### Modelo Jerárquico Dixon-Coles con PyMC

## 📖 Descripción

Este proyecto implementa un **Modelo Jerárquico Dixon-Coles** utilizando **PyMC** para estimar la fortaleza ofensiva y defensiva de las selecciones nacionales y predecir los resultados de los partidos del **Mundial FIFA 2026** mediante inferencia bayesiana.

El modelo incorpora información histórica de encuentros internacionales, variables de rendimiento de cada selección y un enfoque jerárquico que permite compartir información entre equipos, reduciendo el sobreajuste y mejorando la capacidad predictiva.

---

## 🎯 Objetivos

* Construir un modelo probabilístico para la predicción de resultados de fútbol.
* Estimar parámetros ofensivos y defensivos mediante inferencia bayesiana.
* Implementar el modelo Dixon-Coles con una estructura jerárquica.
* Incorporar covariables para mejorar la estimación de los parámetros.
* Realizar simulaciones predictivas para partidos del Mundial FIFA 2026.

---

## 🧠 Modelo utilizado

El proyecto está basado en el modelo **Dixon-Coles**, ampliamente utilizado en analítica deportiva para modelar goles en partidos de fútbol.

La implementación incorpora:

* Modelo Bayesiano Jerárquico.
* Distribuciones de Poisson para el número de goles.
* Priors jerárquicos para ataque y defensa.
* Covariables para mejorar las distribuciones a priori.
* Inferencia mediante **MCMC (Markov Chain Monte Carlo)** utilizando PyMC.

---

## 📂 Estructura general del notebook

El desarrollo sigue un flujo completo de Ciencia de Datos:

1. Configuración del entorno.
2. Configuración del proyecto.
3. Verificación de archivos.
4. Carga de datos.
5. Limpieza y validación.
6. Diagnóstico de calidad.
7. Tratamiento de valores faltantes.
8. Preparación de datos.
9. Identificación automática de variables.
10. Construcción del índice de selecciones.
11. Validación del índice.
12. Definición de coordenadas para PyMC.
13. Construcción de covariables.
14. Definición de priors jerárquicos.
15. Construcción de medias a priori.
16. Integración de covariables.
17. Construcción del modelo probabilístico.
18. Ajuste mediante inferencia bayesiana.
19. Evaluación y análisis de resultados.
20. Predicción de partidos.

---

## 📊 Variables consideradas

El modelo puede utilizar información como:

* Ranking FIFA.
* Fortaleza ofensiva.
* Fortaleza defensiva.
* Historial de partidos.
* Equipo local o visitante.
* Goles anotados.
* Goles recibidos.
* Covariables adicionales para mejorar los priors.

---

## 🛠 Tecnologías utilizadas

* Python 3
* PyMC
* ArviZ
* NumPy
* Pandas
* SciPy
* Matplotlib
* Jupyter Notebook

---

## 🚀 Instalación

Clonar el repositorio:

```bash
git clone https://github.com/tu_usuario/tu_repositorio.git
```

Entrar al proyecto:

```bash
cd tu_repositorio
```

Instalar las dependencias:

```bash
pip install -r requirements.txt
```

Ejecutar el notebook:

```bash
jupyter notebook
```

---

## 📈 Flujo del proyecto

```text
Datos históricos
        │
        ▼
Limpieza y validación
        │
        ▼
Preparación de variables
        │
        ▼
Construcción del modelo Dixon-Coles
        │
        ▼
Modelo Bayesiano Jerárquico
        │
        ▼
Inferencia MCMC con PyMC
        │
        ▼
Estimación de parámetros
        │
        ▼
Predicción de resultados
```

---

## 📌 Características del modelo

* Enfoque completamente bayesiano.
* Priors jerárquicos.
* Modelo probabilístico interpretable.
* Estimación de incertidumbre.
* Escalable a nuevas temporadas.
* Fácil incorporación de nuevas covariables.
* Predicción mediante simulaciones posteriores.

---

## 📚 Referencias

* Dixon, M. J., & Coles, S. G. (1997). *Modelling Association Football Scores and Inefficiencies in the Football Betting Market.*
* Gelman, A., et al. *Bayesian Data Analysis.*
* Documentación oficial de PyMC.
* Documentación oficial de ArviZ.

---

## 👨‍💻 Autor

**Kevin**

Proyecto desarrollado con fines académicos para el estudio de modelos probabilísticos, inferencia bayesiana y analítica deportiva aplicada a la predicción de resultados del **Mundial FIFA 2026**.
