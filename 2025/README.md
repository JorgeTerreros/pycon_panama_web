# Reflex App 🚀

Este proyecto utiliza **Reflex**, un framework moderno para construir aplicaciones web full-stack en Python de manera sencilla.

## 📦 Requisitos

- Python 3.8 o superior
- pip
- Git (opcional, pero recomendado)

## 🔧 Instalación

1. **Clona este repositorio**

git clone https://github.com/pythonpanama/pycon_panama_web.git
cd 2025

2. Crea y activa un entorno virtual (opcional, pero recomendado)

python3 -m venv .venv
source env/bin/activate  # En Windows: .\env\Scripts\activate

3. Instala Reflex

pip install reflex


4. (Opcional) Instala dependencias adicionales

pip install -r requirements.txt


## 🚀 Cómo usar Reflex
1. Inicializa el proyecto (si aún no lo has hecho)

reflex init nombre_proyecto
cd nombre_proyecto


2. Ejecuta la aplicación en modo desarrollo
reflex run

Esto abrirá la aplicación en tu navegador en http://localhost:3000.

## 📁 Estructura del proyecto

.
├── assets/                     # Archivos estáticos (imágenes, CSS, JS)
│   ├── js/
│   ├── bootstrap.min.css
│   ├── styles.css
│   └── ...
│
├── my_first_page/             # Módulo principal de la app
│   ├── components/            # Componentes reutilizables
│   ├── styles/                # Archivos de estilo personalizados
│   ├── views/                 # Vistas o páginas
│   ├── __init__.py
│   ├── constants.py           # Constantes globales
│   └── my_first_page.py       # Archivo principal del frontend
│
├── public/                    # Archivos públicos (usualmente para deploy)
│
├── .states/                   # Estado persistente de Reflex
├── .web/                      # Archivos generados para la versión web
├── .venv/                     # Entorno virtual (no incluir en Git)
├── .gitignore
├── requirements.txt           # Dependencias del proyecto
├── rxconfig.py                # Configuración de Reflex
└── pyrightconfig.json         # Configuración opcional para Pyright (linter)


## 📚 Recursos
https://reflex.dev/
