# â° Digital Clock Simulation in Java

<p align="center">
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/Utility-Time_Formatting-007396?style=for-the-badge" alt="Utility" />
  <img src="https://img.shields.io/badge/Academic-1Âº_DAW_STUCOM-10B981?style=for-the-badge" alt="STUCOM" />
</p>

> ðŸŽ“ **Academic Project Notice:** Developed as an academic practical exercise for the **1st year of Web Application Development (DAW)** at **STUCOM Pelai** (Barcelona) within the Programming Foundations module.

---

## ðŸ“Œ Overview / DescripciÃ³n General

### ðŸ‡¬ðŸ‡§ English
A digital clock simulator and time formatting utility developed in **Java**. It demonstrates control loops, time arithmetic, digit encapsulation, and console visualization of a synchronized real-time digital clock display.

### ðŸ‡ªðŸ‡¸ EspaÃ±ol
Simulador de reloj digital y formateador de tiempo implementado en **Java**. Demuestra el manejo de bucles de control, aritmÃ©tica temporal, encapsulaciÃ³n de horas, minutos y segundos, y representaciÃ³n formateada en consola en tiempo real.

---

## âš™ï¸ Features

- â±ï¸ **Time Arithmetic:** Precise incrementation handling overflow across seconds, minutes, and 24-hour cycles.
- ðŸ“Ÿ **Standard Display Format:** Consistent HH:mm:ss digital output with zero-padding.
- ðŸ§ª **Unit Testability:** Independent time calculations and boundary condition verification (e.g. 23:59:59 roll-over).

---

## ðŸš€ How to Run

`ash
mvn clean compile
mvn exec:java -Dexec.mainClass="com.mycompany.relojdigital.RelojDigital"
`

---

## ðŸ“„ License

Distributed under the **MIT License**.
