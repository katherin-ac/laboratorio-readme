# Calculadora Web
Proyecto en desarrollo

![Estado](https://img.shields.io/badge/version-1.0-blue)

## Descripción

Herramienta que permite hacer operaciones básicas matemáticas (sumar, restar, dividir, multiplicar) en el navegador.


## Tabla de contenidos
- [Descripción](#descripción)
- [Instalación](#instalación)
- [Uso](#uso)
- [Contribuidores](#contribuidores)
- [Funcionalidades](#funcionalidades)
- [Tareas pendientes](#tareas-pendientes)
- [Arquitectura](#arquitectura)

## Instalación
 
```bash
git clone https://github.com/katherin-ac/laboratorio-readme.git
cd laboratorio-readme
npm install
```

## Uso

```bash
npm start
```

## Funcionalidades
| Función | Estado |
|---------|--------|
|  Sumar  |  Listo |
|  Restar |  Listo |
|  Multiplicar | Listo |
|  Dividir |  Listo |

## Tareas pendientes
- [ ] Implementar operaciones matemáticas avanzadas
- [x] Añadir historial de operaciones
- [x]  Diseño responsive
- [ ] Implementar pantalla para gráficos

## Arquitectura

```mermaid
graph LR
    A[Usuario] --> B[Interfaz]
    B --> C[Lógica JS]
    C --> D[Resultado] 
```
## Contribuidores
- Katherin Arapa Catari ([@katherin-ac](https://github.com/katherin-ac))