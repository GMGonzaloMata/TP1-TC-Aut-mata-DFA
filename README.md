# Simulador de Autómata Finito Determinista (DFA) - Cantidad Par de Ceros

Este proyecto es un simulador gráfico de un **Autómata Finito Determinista (DFA)** que reconoce cadenas binarias (compuestas por `0` y `1`) que contienen una **cantidad par de ceros**.

## 📚 Descripción

- **Alfabeto:** `{0, 1}`
- **Estados:**
  - `q0`: Estado inicial y aceptador (cantidad par de ceros)
  - `q1`: Estado (cantidad impar de ceros)
- **Estado inicial:** `q0`
- **Estados finales:** `{q0}`
- **Transiciones:**
  - `(q0, 0) -> q1`
  - `(q0, 1) -> q0`
  - `(q1, 0) -> q0`
  - `(q1, 1) -> q1`

El simulador permite:

- Ingresar una cadena de `0` y `1`.
- Ejecutar la simulación **paso a paso**.
- Visualizar el **estado actual** en cada paso.
- Consultar la **tabla de transiciones** en pantalla.
- Ver si la cadena es **aceptada** o **rechazada** al finalizar.

---

## 🛠️ Tecnologías utilizadas

- **Python 3**
- **Tkinter** (interfaz gráfica estándar de Python)
- **ttk.Treeview** (para mostrar la tabla de transiciones)

---

## 🚀 Cómo ejecutar el simulador

1. Asegúrese de tener instalado **Python 3** en su máquina.
2. Clone este repositorio o descargue los archivos.
3. Ejecute el archivo:

```bash
python dfa_par_ceros.py
```
