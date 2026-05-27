# Lab 9 — MM3014 Teoría de Probabilidades

Laboratorio 9 (Etapa 5) — Simulación del álbum real FIFA 2026  
Diego Calderón (241263) y Pedro Caso (241286)

## Cómo correr el notebook

### 1. Crear entorno virtual

```bash
python -m venv .venv
source .venv/bin/activate        # Linux / macOS
# .venv\Scripts\activate         # Windows
```

### 2. Instalar dependencias

```bash
pip install -r requirements.txt
```

### 3. Lanzar Jupyter

```bash
jupyter notebook lab9.ipynb
```

O para abrir el servidor general:

```bash
jupyter notebook
```

### 4. Correr todas las celdas

Dentro del notebook: **Kernel → Restart & Run All**

---

## Estructura del proyecto

```
Lab9prob1/
├── lab9.ipynb          # Notebook principal
├── requirements.txt    # Dependencias Python
└── README.md           # Este archivo
```

## Parámetros clave

| Variable | Valor |
|----------|-------|
| N (estampas) | 980 |
| S (por sobre) | 7 |
| R (simulaciones) | 5,000 |
| Semilla | 2026 |
| Precio sobre | Q 9.50 |
| Precio caja (104 sobres) | Q 975.00 |
