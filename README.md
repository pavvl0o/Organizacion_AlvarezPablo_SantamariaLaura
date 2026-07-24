# Compuertas Lógicas en HDL

## Contexto

Este repositorio corresponde a la primera actividad del curso de Organización de Computadores. El objetivo fue diseñar un conjunto de circuitos lógicos utilizando HDL (Hardware Description Language).

## Descripción general

El desarrollo sigue un enfoque incremental: cada compuerta se implementa reutilizando las compuertas ya construidas anteriormente. De esta manera, a partir de operaciones lógicas simples de un bit, se llega a circuitos capaces de operar sobre buses de 16 bits y de seleccionar entre múltiples entradas o salidas, sentando las bases para el diseño de componentes de hardware más complejos en etapas posteriores del curso.

## Compuertas implementadas

**Compuertas básicas**
- Not
- And
- Or
- Xor

**Selectores**
- Mux
- DMux

**Versiones de 16 bits**
- Not16
- And16
- Or16
- Mux16

**Compuertas de múltiples entradas o salidas**
- Or8Way
- Mux4Way16
- Mux8Way16
- DMux4Way
- DMux8Way

## Herramientas

Los circuitos fueron descritos en archivos `.hdl` y verificados mediante los scripts de prueba (`.tst`) y archivos de comparación (`.cmp`) provistos por el simulador de hardware del curso.

## Estructura del proyecto

```
├── Not.hdl
├── And.hdl
├── Or.hdl
├── Xor.hdl
├── Mux.hdl
├── DMux.hdl
├── Not16.hdl
├── And16.hdl
├── Or16.hdl
├── Mux16.hdl
├── Or8Way.hdl
├── Mux4Way16.hdl
├── Mux8Way16.hdl
├── DMux4Way.hdl
└── DMux8Way.hdl
```
