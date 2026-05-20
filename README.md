# TPFINAL_REAL
# 🧪 Trabajo Práctico Final - Testeo de Software

![GitHub last commit](https://img.shields.io/github/last-commit/tomas-maker2/TrabajoFinaL?style=flat-square&color=blue)
![GitHub top language](https://img.shields.io/github/languages/top/tomas-maker2/TrabajoFinaL?style=flat-square)
![Jest Tests](https://img.shields.io/badge/tests-passing-brightgreen?style=flat-square&logo=jest)

Bienvenido al repositorio del código fuente y conjunto de pruebas para el Trabajo Práctico Final de la materia **Testeo de Software (3)**.

---

## 🎓 Información Académica

| Rol | Detalle |
| :--- | :--- |
| **Institución** | Universidad de Belgrano 🏛️ |
| **Facultad** | Facultad de Ingeniería y Tecnología Informática 💻 |
| **Carrera** | Técnico en Programación de Computadoras 👨‍💻 |
| **Plan de Estudios** | 2014 - Año 2023 📅 |
| **Alumno** | [Tu Nombre y Apellido] 👤 |

---

## 📝 1. Descriptivo del Software

### 🎯 Objetivo del Software
El objetivo de este proyecto es proveer un módulo de cálculos matemáticos precisos y fiables. Permite resolver operaciones aritméticas asegurando un manejo de errores robusto, diseñado específicamente para ser sometido a un ciclo de testing de software completo (Unitario, Integración, Caja Negra, Rendimiento y E2E).

> **A continuación, una vista previa de la interfaz del software:**
>
> *[Nota para vos: Subí una foto de tu sistema y reemplazá el link]*
> ![Vista previa de la app](./assets/screenshot.png)

### ⚙️ Requerimientos Funcionales (RF)
* **RF01:** El sistema debe permitir el ingreso de dos valores numéricos.
* **RF02:** El sistema debe ejecutar operaciones matemáticas básicas (suma, resta, multiplicación, división).
* **RF03:** El sistema debe validar las reglas matemáticas básicas (ej: impedir y notificar la división por cero).

### 🚀 Requerimientos No Funcionales (RNF)
* **RNF01:** El sistema debe estar desarrollado bajo el paradigma de Orientación a Objetos.
* **RNF02:** El tiempo de procesamiento de cada cálculo debe ser inferior a 200 milisegundos.
* **RNF03:** El código debe ser modular para permitir la inyección de pruebas unitarias mediante frameworks de testing.

---

## 📊 Artefactos UML

Para el diseño de este sistema, se implementó el siguiente modelo orientado a objetos, donde se puede observar la interacción entre la interfaz y el motor matemático:

> *[Nota para vos: Subí la foto de tu diagrama de clases o casos de uso a tu repo]*
> ```mermaid
classDiagram
    class CalculatorController {
        +add(a: Number, b: Number) Number
        +subtract(a: Number, b: Number) Number
        +divide(a: Number, b: Number) Number
        +calcularDescuento(monto: Number, esClienteVIP: Boolean) Number
    }
    
    class UI {
        +ingresarDatos()
        +mostrarResultado()
        +mostrarError()
    }
    
    UI --> CalculatorController : "Envía datos"
    CalculatorController --> UI : "Retorna resultado/error"
```
---

## 🛠️ Tecnologías Utilizadas

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![NodeJS](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![Jest](https://img.shields.io/badge/Jest-C21325?style=for-the-badge&logo=jest&logoColor=white)
![Git](https://img.shields.io/badge/GIT-E44C30?style=for-the-badge&logo=git&logoColor=white)

---

## 💻 Instalación y Ejecución

1. **Clonar el repositorio:**
   ```bash
   git clone [https://github.com/tomas-maker2/TrabajoFinaL.git](https://github.com/tomas-maker2/TrabajoFinaL.git)
   npm install
   npm start

   npm test[README.md](https://github.com/user-attachments/files/28075373/README.md)
