[ 🌐 عربي ](README.ar.md) | [ 🇩🇪 Deutsch ](README.de.md) | [ 🇫🇷 Français ](README.fr.md) | [ 🇳🇱 Nederlands ](README.nl.md) | [ 🇪🇸 Español ](README.sp.md) | [ 🇬🇧 English ](README.md)

# Calculadora de IVA para Shopify y Etsy: Plantilla y libro de trabajo de cumplimiento fiscal multipaís

![License: Apache 2.0](https://img.shields.io/badge/License-Apache%202.0-blue.svg)
![Platform: Browser + Excel](https://img.shields.io/badge/Platform-Browser%20%2B%20Excel-green.svg)
![Tool Type: VAT Compliance & Decision Support](https://img.shields.io/badge/Tool-VAT%20Decision%20Support-orange.svg)

**Automatiza el cumplimiento fiscal de tu ecommerce transfronterizo con esta calculadora gratuita de IVA (impuesto sobre el valor añadido) para Shopify y Etsy. Esta plantilla de Excel reutilizable y herramienta contable basada en navegador concilia al instante las declaraciones mensuales de IVA multipaís, las declaraciones OSS (One-Stop Shop, ventanilla única) y las obligaciones fiscales sobre ventas, eliminando los errores manuales de hoja de cálculo sin necesidad de una suscripción de software.**

**Sin registro. Sin instalación. Gratis en tu navegador.**

Prueba los datos de tus transacciones en la versión gratuita del navegador. Para una contabilidad mensual recurrente, actualiza al formato de Excel descargable (con una garantía de devolución de 30 días sin preguntas).
>
> 🌐 **Ejecuta la conciliación fiscal al instante** → [*Prueba la app gratuita de calculadora de IVA en el navegador*](https://hyvoid.github.io/shopify-etsy-vat-calculator/)
>
> 📥 **Automatiza las declaraciones mensuales** → [*Descarga la plantilla reutilizable de contabilidad de IVA en Excel*](https://www.theseusworkshop.com/l/ytjhap?utm_source=github&utm_medium=GitHub%20README&utm_campaign=readme%20new%20launch&utm_content=shopify-etsy-vat-dashboard)
>
> Disponible en formatos de **software HTML basado en navegador** y **libro de Excel sin macros**.

---

## Puntos débiles del IVA en ecommerce y soluciones automatizadas (Qué te ayuda a controlar)

En lugar de enumerar métricas básicas, así es como esta plantilla de conciliación fiscal conecta los puntos débiles de tu contabilidad de ecommerce con soluciones de declaración prácticas:

* **Punto débil:** Exportaciones CSV fragmentadas de múltiples canales.
  * **Solución:** Consolida el IVA mensual a pagar por país de Shopify y Etsy en un *único libro de registro de reporting*.
* **Punto débil:** Cifras de ingresos netos opacas.
  * **Solución:** Calcula simultáneamente ventas brutas, ventas netas, IVA devengado, IVA de reembolsos y las obligaciones fiscales finales para un reporting listo para auditoría.
* **Punto débil:** Errores silenciosos en la asignación de jurisdicciones fiscales.
  * **Solución:** Marca las transacciones con asignaciones de país faltantes, supuestos fiscales incorrectos o inconsistencias de reporting antes de la declaración.
* **Punto débil:** Pago excesivo de impuestos transfronterizos por la lógica de cálculo del marketplace.
  * **Solución:** Audita los importes de impuestos recaudados por la plataforma frente a tus obligaciones de IVA calculadas internamente.
* **Punto débil:** Pérdida de dinero en las devoluciones de clientes.
  * **Solución:** Automatiza las recuperaciones de IVA por reembolsos que, de lo contrario, se omitirían en tus declaraciones OSS.
* **Punto débil:** Ansiedad de última hora en la declaración.
  * **Solución:** Proporciona un estado definitivo de preparación antes de presentar declaraciones de IVA u OSS a la autoridad fiscal.

---

# Por qué construí esta herramienta de conciliación fiscal

La mayoría de las pequeñas y medianas empresas de ecommerce transfronterizo no tienen dificultades porque las normas de IOSS (Import One-Stop Shop) o del IVA de la UE sean imposibles de entender.

Tienen dificultades porque los cálculos de IVA se fragmentan entre las plataformas de la tienda, las exportaciones CSV en bruto, los contables externos, los marketplaces y las jurisdicciones fiscales locales.

Un flujo de trabajo contable manual típico suele ser así:
1. Exporta los informes financieros de Shopify.
2. Exporta los extractos de transacciones de Etsy.
3. Pega los datos en bruto en hojas de cálculo separadas y frágiles.
4. Calcula manualmente el IVA específico de cada jurisdicción.
5. Compara los impuestos recaudados por el marketplace con los supuestos contables.
6. Descubre discrepancias fiscales durante la preparación nocturna de la declaración.

El verdadero fallo analítico no son las «fórmulas de Excel fiscales incorrectas». El fallo es **tomar decisiones fiscales sin un modelo unificado, a nivel de transacción, de tu obligación de impuesto sobre ventas**.

Por ejemplo:

| Escenario de evaluación fiscal | Contabilidad manual tradicional |
| ----------------------- | ----------------------------- |
| Ventas brutas de Alemania (DE)| €42,800                       |
| Tipo de IVA local supuesto  | 19%                           |
| Impuesto recaudado por Shopify   | €6,750                        |
| IVA calculado real   | €6,832                        |
| **Desviación de conciliación**| **€82**                    |

Una discrepancia de €82 puede parecer irrelevante. Sin embargo, multiplicada por cuatro países de la UE, dos plataformas de marketplace, cientos de reembolsos y periodos trimestrales de declaración OSS, el problema se convierte en un fallo sistémico de conciliación en lugar de un simple error de cálculo.

Este libro de trabajo convierte en producto un marco analítico de ecommerce repetible:

> **Importa las exportaciones en bruto una vez → normaliza los datos automáticamente una vez → valida las anomalías una vez → genera resultados de declaración fiscal precisos de forma repetida.**

El objetivo no es la automatización por sí misma. El objetivo es saber:
> **«¿Puede presentarse la declaración de IVA multipaís de este mes a la autoridad fiscal con un 100 % de confianza?»**

---

## Comparación de cumplimiento de IVA: flujo manual frente a automatizado

| Problema común de cumplimiento fiscal    | Flujo de contabilidad manual tradicional | Solución automatizada del libro de IVA             |
| ---------------------------------------- | -------------------------------------- | ------------------------------------------- |
| **Fragmentación de ventas multiplataforma**   | Consolidar manualmente los datos de Shopify y Etsy mediante VLOOKUP | Ingesta de datos en un libro de transacciones unificado preconstruido |
| **Faltan asignaciones de impuestos transfronterizos**    | Descubrir errores de reporting tarde, al subir al portal de declaración | Marcar automáticamente las jurisdicciones faltantes en el panel de validación |
| **Desviaciones entre marketplace e impuesto real** | Realizar una conciliación manual línea por línea de la lógica de la plataforma | Activar la detección automática de desviaciones para discrepancias > €1.00 |
| **Tratamiento de la compensación del IVA de reembolsos**          | Omitir la recuperación del impuesto de reembolsos, lo que provoca pagos en exceso | Calcular automáticamente las compensaciones de IVA de reembolsos para deducciones precisas |
| **Preparación mensual de la declaración**           | Reconstruir la hoja de seguimiento fiscal en cada ciclo de reporting | Generar automáticamente el resultado de declaración estructurado mediante matrices dinámicas |
| **Validación de la preparación para el cumplimiento**      | Depender por completo de la revisión manual de un gestor externo | Apoyarse en un control sistemático de excepciones antes de la presentación fiscal final |

---

## Escenarios reales de cumplimiento de IVA para equipos transfronterizos

Esta plantilla cubre necesidades de flujos de trabajo de alta intención en diversos escenarios operativos:

* **Declaraciones trimestrales de OSS / IOSS:** Agregar las ventas B2C transfronterizas de toda la UE para garantizar un reporting preciso al portal fiscal.
* **Conciliación de marketplaces multicanal:** Tender un puente entre la lógica de impuesto del marketplace facilitator de Etsy y la recaudación independiente de impuestos de los comerciantes de Shopify.
* **Preparación de auditorías y copia de seguridad del libro:** Mantener una copia de seguridad a nivel de transacción de todos los cálculos fiscales para defenderse de auditorías fiscales jurisdiccionales.
* **Análisis de rentabilidad y margen neto:** Extraer el componente de IVA de los pagos brutos del marketplace para conocer los verdaderos ingresos netos del producto.

---

## Para quién es esto (roles objetivo y casos de uso)

Esta herramienta está diseñada explícitamente para vincular roles concretos con sus cuellos de botella operativos:

* **Comerciantes internacionales de Shopify** que necesitan una *plantilla automatizada de cálculo del IVA de la UE* para reemplazar hojas de cálculo manuales propensas a errores.
* **Vendedores de Etsy** que buscan un *software mensual de seguimiento del cumplimiento fiscal* que gestione automáticamente las compensaciones por reembolsos.
* **Responsables financieros de ecommerce** que buscan una *hoja de conciliación fiscal multicanal* para unificar flujos de datos distintos.
* **CFOs fraccionarios y contables** que gestionan múltiples carteras de clientes con un *panel contable transfronterizo* estandarizado.
* **Consultores de IVA** que requieren un *libro robusto de diagnóstico y validación fiscal* para la incorporación de clientes.

Esta herramienta **no** está diseñada para:
* Proyectos de sustitución de ERP (p. ej., NetSuite o SAP).
* Motores fiscales globales empresariales (p. ej., Avalara o Vertex).
* Pasarelas API de declaración fiscal automatizada.
* Plugins de cálculo fiscal transaccional en tiempo real en el checkout.

No se requiere experiencia avanzada en hojas de cálculo.

---

## Flujo de inicio rápido: concilia tu primera declaración de IVA

Sigue este protocolo operativo simplificado para auditar tus obligaciones fiscales hoy mismo:

1. **Exporta los datos de la plataforma:** Descarga tus informes CSV estándar de transacciones desde los paneles de comercio de Shopify y Etsy para el mes de reporting objetivo.
2. **Ejecuta el diagnóstico:** Pega tus datos en bruto en la [*Calculadora de IVA gratuita en el navegador*](https://hyvoid.github.io/shopify-etsy-vat-calculator/) para realizar una comprobación instantánea de la salud fiscal.
3. **Resuelve las excepciones:** Usa el Centro de Validación para identificar códigos de país sin asignar, alertas de desviación e impuestos de reembolsos no recuperados.
4. **Automatiza las declaraciones futuras:** Una vez limpios tus datos, genera tu informe final de declaración de IVA. Para operaciones mensuales continuas, **[descarga el libro de Excel reutilizable de IVA](https://www.theseusworkshop.com/l/ytjhap?utm_source=github&utm_medium=GitHub%20README&utm_campaign=readme%20new%20launch&utm_content=shopify-etsy-vat-dashboard)** para guardar tus asignaciones de jurisdicción personalizadas, eliminar la configuración repetitiva y estandarizar permanentemente tu cumplimiento transfronterizo.

---

## Detalles técnicos

<details>
<summary>Para revisores técnicos, profesionales de la contabilidad en Excel y analistas financieros</summary>

---

### Arquitectura del libro de trabajo

El libro sigue una arquitectura analítica de cuatro capas diseñada para la integridad de los datos financieros:

```text
DATA INPUT
    ↓
NORMALIZATION ENGINE
    ↓
VAT CALCULATION ENGINE
    ↓
VALIDATION CENTER
    ↓
MONTHLY VAT REPORT (AUDIT-READY)

```

| Nombre de la hoja | Capa de arquitectura | Propósito contable principal |
| --- | --- | --- |
| Control Panel | Presentación | Parámetros y seguimiento de KPI |
| Shopify Import | Ingesta de datos | Ingesta del CSV en bruto de Shopify |
| Etsy Import | Ingesta de datos | Ingesta del CSV en bruto de Etsy |
| Normalization Engine | Ingeniería de datos | Libro de transacciones unificado |
| VAT Calculation Engine | Cálculo | Cómputo y asignación de impuestos |
| Validation Center | Aseguramiento de calidad | Detección de excepciones |
| Monthly VAT Report | Salida | Reporting listo para declaración |

**Regla práctica:** La validación siempre ocurre antes de que los resultados de reporting sean operativamente fiables.

---

### Tres trampas que atrapan incluso a equipos financieros de ecommerce con experiencia

#### Trampa 1 — Suponer que el impuesto de la plataforma es igual a la obligación fiscal real

1. Se tomó una decisión de declaración fiscal.
2. La decisión se basó únicamente en los importes de impuestos recaudados por el marketplace.
3. La lógica fiscal de la plataforma difería de las normas de la jurisdicción de declaración local.
4. El importe final declarado resultó inexacto.

| Métrica | Plataforma del marketplace | Obligación real |
| --- | --- | --- |
| Ventas brutas | €50,000 | €50,000 |
| Impuesto de la plataforma | €7,600 | — |
| IVA calculado | — | €8,042 |

**Conclusión incorrecta:**

```text
VAT payable = Platform tax collected

```

**Enfoque correcto:**

```text
VAT payable = Gross Sales - Net Sales - Refund VAT adjustments

```

```excel
Net Sales = Gross/(1+VAT Rate)
Output VAT = Gross-Net Sales
Net VAT Payable = Output VAT-Refund VAT

```

---

#### Trampa 2 — Ignorar la recuperación del impuesto de los reembolsos

1. Se produjeron reembolsos a clientes.
2. Se omitieron los cálculos de recuperación del IVA.
3. La obligación fiscal total permaneció sobreestimada, filtrando margen neto.

| Partida del libro | Sin recuperación del impuesto | Con recuperación del impuesto |
| --- | --- | --- |
| IVA de ventas | €12,300 | €12,300 |
| IVA de reembolsos | €0 | €1,120 |
| IVA final | €12,300 | €11,180 |

El error analítico crítico es tratar los reembolsos como ajustes de ingresos brutos en lugar de ajustes específicos de la obligación fiscal.

```excel
Refund VAT = Refund Amount × VAT Rate ÷ (1+VAT Rate)

```

---

#### Trampa 3 — Suponer que los códigos de país de los clientes son siempre precisos

1. Se ejecutaron los cálculos de declaración.
2. Las asignaciones de país por defecto contenían datos en blanco o erróneos.
3. La asignación de jurisdicciones de IVA se volvió fundamentalmente defectuosa.

Ejemplo de fallo silencioso:

| ID de transacción | País de facturación |
| --- | --- |
| TX-10025 | DE |
| TX-10026 | BLANK |
| TX-10027 | XX |

Sin validación programática, estas transacciones sin asignar entran silenciosamente en tus declaraciones fiscales finales.

**Enfoque de validación corregido:**

```text
IF Country is missing
OR VAT rate is unmapped
OR Tax variance > threshold
THEN Generate Exception Flag

```

```excel
err_country = country=""
err_unmapped = vat_rate=0
err_tax = ABS(platform-calculated)>1

```

---

### Referencia de fórmulas y dependencias

```excel
FILTER()
VSTACK()
CHOOSECOLS()
MAP()
LET()
HSTACK()

```

*Propósito:* Eliminar filas vacías, normalizar el esquema de la plataforma, estandarizar códigos de país, construir el libro de transacciones.

```excel
XLOOKUP()
SUMIFS()
MAP()

```

*Propósito:* Búsqueda dinámica de IVA, asignación fiscal por jurisdicción, extracción de recuperaciones por reembolso, cálculo del neto a pagar.

```excel
FILTER()
TEXTJOIN()
ABS()
IF()
LET()

```

*Propósito:* Detección de excepciones, generación de paquetes de diagnóstico, pasarela de control de la declaración fiscal.

</details>

---

## La lógica de negocio y la metodología

Esta herramienta no es solo una hoja de cálculo; es una metodología operativa diseñada para proteger tu margen neto y garantizar la preparación para auditorías. Resuelve el problema central de negocio de la **fragmentación financiera multicanal** aplicando principios de conciliación de nivel empresarial al ecommerce transfronterizo de las pymes.

Esta es la metodología que impulsa el sistema:

### 1. Normalización de datos (fuente única de verdad)
*   **El problema de negocio:** Shopify y Etsy exportan datos de transacciones en esquemas de reporting completamente distintos. Compararlos manualmente provoca caos de control de versiones y VLOOKUP rotos.
*   **La metodología:** La herramienta actúa como un pipeline ETL (extraer, transformar, cargar) ligero. Ingiere automáticamente exportaciones CSV en bruto dispares y las normaliza en un libro de transacciones unificado y estandarizado, creando una fuente única de verdad para tus datos de cumplimiento.

### 2. Recálculo fiscal de confianza cero
*   **El problema de negocio:** Confiar ciegamente en las cifras de «impuesto recaudado» del marketplace suele provocar errores de declaración por jurisdicción, ya que los algoritmos de la plataforma pueden no alinearse con tus obligaciones concretas de nexus ni con las clases de impuesto de tus productos.
*   **La metodología:** El motor utiliza un modelo de cálculo de «confianza cero». Recalcula tu verdadera obligación fiscal *de abajo hacia arriba* a partir de las ventas brutas y tus tipos jurisdiccionales configurados, y luego audita esta línea base contra el impuesto recaudado por la plataforma para revelar desviaciones ocultas de cálculo.

### 3. Gestión por excepciones
*   **El problema de negocio:** Revisar manualmente miles de microtransacciones cada mes para preparar una declaración OSS es un drenaje insostenible de recursos financieros.
*   **La metodología:** La arquitectura traslada tu flujo contable a la «gestión basada en excepciones». En lugar de auditar cada fila, el Centro de Validación aísla solo las anomalías —códigos de país faltantes, tipos impositivos en blanco o desviaciones de recaudación superiores a €1.00—, lo que te permite centrarte únicamente en la resolución de problemas de alto impacto.

### 4. Recuperación del margen neto mediante compensaciones por reembolsos
*   **El problema de negocio:** Muchos comerciantes transfronterizos tratan las devoluciones de clientes puramente como deducciones de ingresos y no recuperan sistemáticamente el IVA devengado asociado, filtrando así beneficio neto hacia las autoridades fiscales.
*   **La metodología:** El motor de cálculo aísla programáticamente las transacciones de reembolso y las mapea de vuelta a sus jurisdicciones de origen. Aplica automáticamente compensaciones de crédito fiscal contra tu IVA bruto a pagar, asegurando que nunca absorbas el coste fiscal de las ventas reembolsadas.

---


## Otras herramientas operativas de esta serie

* **Inventory Planning & Replenishment Console** — plantilla de optimización de reordenación y gestión del riesgo de existencias.
* **Marketing Attribution Audit System** — validación de atribución de canales y análisis de eficiencia de ROAS.
* **Project Cost Allocation Workbench** — hoja de cálculo de asignación de mano de obra y seguimiento de la rentabilidad de proyectos.
* **Multi-Entity Logistics Control Tower** — panel de monitorización de envíos transfronterizos y aduanas.

Explora más marcos de apoyo a la decisión y plantillas a través del perfil de GitHub y nuestro [sitio web](https://www.theseusworkshop.com/).

---

## Licencia

Este proyecto está licenciado bajo la **Apache License 2.0**.

Consulta el archivo LICENSE para más detalles.
