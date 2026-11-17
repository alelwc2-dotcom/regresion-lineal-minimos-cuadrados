# Regresión Lineal Simple por Mínimos Cuadrados (Java)

Implementación en Java del método numérico de **Regresión Lineal Simple por Mínimos Cuadrados**, incluyendo el cálculo del **Coeficiente de Correlación de Pearson ($r$)** y el **Coeficiente de Determinación ($r^2$)**, desarrollado para la asignatura **SCC-1017 Métodos Numéricos** (Unidad 5: Ajuste de Funciones).

## Estructura del Proyecto

```text
├── Ajuste_de_Funciones/
│   └── RegresionLineal.java
└── README.md
```

## Requisitos Previos

* **Java Development Kit (JDK)** 8 o superior instalado.
* **Git** instalado para clonar el repositorio.

## Instrucciones de Uso

1. **Clonar el repositorio:**
   ```bash
   git clone https://github.com/alelwc2-dotcom/regresion-lineal-minimos-cuadrados.git
   cd regresion-lineal-minimos-cuadrados
   ```

2. **Compilar el código fuente:**
   ```bash
   javac Ajuste_de_Funciones/RegresionLineal.java
   ```

3. **Ejecutar el programa:**
   ```bash
   java Ajuste_de_Funciones.RegresionLineal
   ```

## Funcionalidades

* Cálculo de sumatorias ($\sum x$, $\sum y$, $\sum x^2$, $\sum y^2$, $\sum xy$).
* Obtención de la pendiente ($\beta_1$) y la ordenada al origen ($\beta_0$).
* Cálculo de correlación lineal mediante Pearson ($r$) y bondad de ajuste ($r^2$).
* Función `predecir(beta0, beta1, xValor)` para estimar nuevos valores dependientes.
