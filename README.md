# ⏰ Reloj Digital en Consola (Java)

<p align="center">
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/Algorithms-Time_Carry_Logic-047857?style=for-the-badge" alt="Algorithms" />
  <img src="https://img.shields.io/badge/Academic-1º_DAW_STUCOM-10B981?style=for-the-badge" alt="STUCOM" />
</p>

> 🎓 **Proyecto Académico:** Práctica de algoritmia y estructuras de control en **Java** desarrollada por **Ignacio Breñas Muñoz** para el 1º curso de **Desarrollo de Aplicaciones Web (DAW)** en **STUCOM Pelai** (Barcelona).

---

## Descripción de la Práctica

Implementación de un reloj digital en formato de 24 horas (`HH:MM`) utilizando un array numérico de 4 posiciones `int[4]`. El programa proporciona un menú interactivo en consola para avanzar o retroceder el tiempo (tanto horas como minutos), gestionando rigurosamente los desbordamientos de acarreo horario (0 a 23 horas, 0 a 59 minutos).

---

## 🧠 Funcionamiento Interno

### Representación en Memoria
El reloj se representa mediante un array de dígitos:
```java
int[] reloj = new int[4];
// reloj[0]: Decenas de hora (0-2)
// reloj[1]: Unidades de hora (0-9)
// reloj[2]: Decenas de minuto (0-5)
// reloj[3]: Unidades de minuto (0-9)
```

### Funcionalidades del Menú
- ⏩ **Adelantar Minutos:** Incrementa los minutos y traslada el acarreo a las horas al superar 59 minutos. Al superar las 23:59 vuelve a 00:00.
- ⏪ **Retrasar Minutos:** Decrementa los minutos y descuenta de las horas cuando sea necesario, ciclando a 23:59 al retroceder de 00:00.
- ⏰ **Adelantar Horas:** Incrementa horas completas con ciclo de 24h.
- 🕒 **Retrasar Horas:** Decrementa horas completas con ciclo de 24h.
- 🖥️ **Muestra Formateada:** Imprime siempre la hora con ceros a la izquierda en formato `HH:MM`.

---

## 🚀 Compilación y Ejecución

```bash
# Compilar con Maven
mvn clean compile

# Ejecutar
mvn exec:java -Dexec.mainClass="main.RelojDigital"
```

---

## 👤 Autor

**Ignacio Breñas Muñoz** — 1º DAW, STUCOM Pelai
