# 📡 Apuntes: Cableado Estructurado

> **Sesión:** Estándares, Normativas y Clasificación de Rendimiento en Redes  
> **Área:** Telecomunicaciones / Infraestructura de Red

---

## 📁 Estructura del Repositorio

```
apuntes/
├── README.md                  ← Este archivo
└── cableado-estructurado.md   ← Contenido técnico detallado
```

---

## 📋 Tabla de Contenidos

1. [Estándares y Normativas Internacionales](#i-estándares-y-normativas-internacionales)
2. [El Estándar Maestro: TIA/EIA-568](#ii-el-estándar-maestro-tiaeia-568)
3. [Clasificación de Rendimiento](#iii-clasificación-de-rendimiento)
4. [Glosario de Abreviaciones Técnicas](#iv-glosario-de-abreviaciones-técnicas)
5. [Normas Complementarias](#v-normas-complementarias-el-plus-del-electricista)

---

## I. Estándares y Normativas Internacionales

> ⚠️ **¿Por qué son importantes?**  
> Estos marcos evitan los sistemas **"propietarios"** que atan a las empresas a un solo fabricante. Los estándares abiertos garantizan interoperabilidad, libertad de elección y continuidad a largo plazo.

### TIA — Telecommunications Industry Association

- Organización **norteamericana**
- Enfocada en el rendimiento de componentes e instalación de campo
- Define estándares como el **TIA/EIA-568**

### EIA — Electronic Industries Alliance

- Su legado perdura en la **nomenclatura de estándares actuales**
- El nombre `TIA/EIA-568` refleja la colaboración histórica entre ambas organizaciones

### ISO/IEC — Organismo Internacional de Normalización

- El organismo de normalización **más importante a nivel mundial**
- Su norma **ISO/IEC 11801** es dominante en **Europa y Asia**
- Define "**clases**" que son el equivalente a las "categorías" del sistema TIA

---

## II. El Estándar Maestro: TIA/EIA-568

Define las dos configuraciones de conexión para conectores **RJ45**:

### Configuración T568A

| Pin | Color          |
|-----|----------------|
| 1   | Blanco/Verde   |
| 2   | Verde          |
| 3   | Blanco/Naranja |
| 4   | Azul           |
| 5   | Blanco/Azul    |
| 6   | Naranja        |
| 7   | Blanco/Marrón  |
| 8   | Marrón         |

### Configuración T568B

| Pin | Color          |
|-----|----------------|
| 1   | Blanco/Naranja |
| 2   | Naranja        |
| 3   | Blanco/Verde   |
| 4   | Azul           |
| 5   | Blanco/Azul    |
| 6   | Verde          |
| 7   | Blanco/Marrón  |
| 8   | Marrón         |

> 💡 **Diferencia clave:** En T568A los pares de Verde y Naranja están invertidos respecto a T568B. La T568B es la más utilizada en instalaciones de Norteamérica.  
> Un cable que usa T568A en un extremo y T568B en el otro se denomina **cable cruzado (crossover)**.

---

## III. Clasificación de Rendimiento

Tabla comparativa de **Categorías TIA** vs. **Clases ISO/IEC**:

| Rendimiento | TIA (Categoría) | ISO/IEC (Clase) | Frecuencia Máx. |
|:-----------:|:---------------:|:---------------:|:---------------:|
| 1 Gbps      | Cat 5e          | Clase D         | 100 MHz         |
| 10 Gbps     | Cat 6A          | Clase EA        | 500 MHz         |
| 40 Gbps     | Cat 8           | Clase I/II      | 2000 MHz        |

> 📌 A mayor categoría/clase → mayor frecuencia soportada → mayor velocidad de transmisión.

---

## IV. Glosario de Abreviaciones Técnicas

| Término | Significado | Descripción |
|---------|-------------|-------------|
| **NEXT** | Near-End Crosstalk | Interferencia entre pares de cables medida en el **extremo cercano** (donde se inyecta la señal). |
| **FEXT** | Far-End Crosstalk | Interferencia entre pares de cables medida en el **extremo lejano** (opuesto al emisor). |
| **Return Loss** | Pérdida por Retorno | Medida de la energía reflejada de vuelta debido a variaciones en la **impedancia** del cable. |
| **PoE** | Power over Ethernet | Inyección de voltajes DC (**44V a 57V**) sobre el mismo cable de datos. Alimenta dispositivos como cámaras IP, teléfonos VoIP y APs. |
| **AWG** | American Wire Gauge | Calibre del grosor del cobre. **A número más pequeño → cable más grueso.** Ej: AWG 22 es más grueso que AWG 26. |
| **TR** | Telecommunications Room | **Cuarto de Telecomunicaciones:** espacio donde se concentra el cableado horizontal de una planta. |
| **ER** | Equipment Room | **Cuarto de Equipos:** espacio central que aloja servidores, switches principales y equipos de backbone. |

---

## V. Normas Complementarias: El "Plus" del Electricista

Estas tres normas son determinantes para el éxito en un entorno industrial:

### TIA-569 — Espacios y Canalizaciones

> Define los requisitos para ductos, bandejas portacables, tubería conduit y cualquier elemento que **transporte el cableado** dentro de un edificio.

- Establece dimensiones mínimas de ductos y bandejas
- Define radio de curvatura mínimo para cables
- Aplica a salas de telecomunicaciones, cuartos de equipo y rutas de backbone

---

### TIA-606 — Administración (Etiquetado y Documentación)

> Define el sistema de **identificación, etiquetado y registro** de todos los elementos de la infraestructura de telecomunicaciones.

- Estandariza el formato de etiquetas para cables, paneles y puertos
- Facilita el mantenimiento y la resolución de fallas
- Permite que cualquier técnico entienda la instalación, sin importar quién la realizó

---

### TIA-607 — Puesta a Tierra (Grounding)

> Define los requisitos de **bonding y grounding** para infraestructura de telecomunicaciones.

- Protege equipos contra descargas eléctricas y sobretensiones
- Reduce interferencia electromagnética (EMI)
- Es un requisito de seguridad eléctrica en entornos industriales y de misión crítica

---

## 🔗 Referencias

- [TIA Standards](https://tiaonline.org/)
- [ISO/IEC 11801](https://www.iso.org/standard/61948.html)
- [ANSI/TIA-568](https://tiaonline.org/standards/tia-568/)

---

*Apuntes generados a partir de la sesión de clase. Para uso académico y de referencia.*
