# Proyecto Integrador – Organización y Arquitectura de Computadores

## Estudiantes
Nombre: Pablo Alvarez Restepo
Nombre: Laura Santamaria Espinosa

## Descripción

Este repositorio contiene la solución al Proyecto Integrador del primer corte del curso de Organización y Arquitectura de Computadores.

El proyecto se basa en los Proyectos 1, 2 y 3 de la plataforma Nand2Tetris e incluye una extensión académica denominada ALUExtendida, desarrollada específicamente para este curso.

## Contenido
### Proyecto 1

Implementación de las compuertas lógicas básicas y estructuras combinacionales derivadas.

COMPONENTES
Not
And
Or
Xor
Mux
DMux
Not16
And16
Or16
Mux16
Or8Way
Mux4Way16
Mux8Way16
DMux4Way
DMux8Way



### Proyecto 2

Implementación de circuitos aritméticos y de la ALU.

COMPONENTES
HalfAdder
FullAdder
Add16
Inc16
ALU



### Proyecto 3

Implementación de componentes secuenciales y memoria.

Componentes
Bit
Register
RAM8
RAM64
RAM512
RAM4K
RAM16K
PC



### Extensión: ALUExtendida

La ALUExtendida conserva la interfaz de la ALU original de Nand2Tetris y agrega cinco operaciones nuevas, seleccionables mediante el pin adicional a. La ALU original no fue modificada; la ALUExtendida la reutiliza como componente interno y añade un camino paralelo para las nuevas operaciones, seleccionando la salida final mediante un multiplexor y recalculando las banderas zr y ng sobre dicha salida final.

#### Operaciones soportadas

XOR	--- 010110 --- out = x XOR y
NAND --- 000001 ---	out = !(x AND y)
NOR	--- 110100 ---	out = !(x OR y)
EQ	--- 101000 ---	out = 1 si x = y, out = 0 si x ≠ y
ABS	--- 100010 ---	out = |x| (complemento a dos, y se ignora)



## Estructura del Repositorio

nombre_equipo/
├── proyecto01/
│   ├── HDL
│   └── TESTS
├── proyecto02/
│   ├── HDL
│   └── TESTS
├── proyecto03/
│   ├── HDL
│   └── TESTS
├── alu_extendida/
│   ├── HDL
│   ├── TESTS
│   └── DOCUMENTACION
└── README.md