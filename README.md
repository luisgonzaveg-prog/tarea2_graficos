# tarea2_graficos
Tarea 2 del curso GF-0657 Programación en SIG

# Análisis de la Distribución de Cultivos en Costa Rica

## 1. Tema de Investigación
Distribución y producción de cultivos en Costa Rica.

## 2. Preguntas de Investigación
1. **¿Cuáles son los cultivos con mayor extensión sembrada en Costa Rica?** Esto permite identificar la vocación agrícola predominante del país.
2. **¿Existe una relación directa y proporcional entre el área sembrada y la producción total (en toneladas) de los distintos cultivos?** Esto nos ayudará a comprender si mayor terreno siempre equivale a mayor producción, o si depende de la especie.
3. **¿Cómo ha evolucionado la producción de cultivos tradicionales (como el café) a lo largo de los años?** Para observar la dinámica temporal de un cultivo clave.

## 3. Fuentes de Datos
Para este análisis, emplearemos dos conjuntos de datos clave recopilados a partir de las principales autoridades estadísticas del país:
- **INEC (Instituto Nacional de Estadística y Censos):** Encuesta Nacional Agropecuaria (ENA). Datos sobre área sembrada, cosechada y producción de cultivos.
- **MAG/SEPSA (Ministerio de Agricultura y Ganadería):** Costa Rica. Extensión sembrada y producción de las principales actividades agrícolas.

## 4. Descripción de las Variables Principales
- **Cultivo / Actividad:** Nombre del producto agrícola.
- **Área sembrada (ha):** Superficie destinada a la siembra.
- **Área cosechada (ha):** Superficie de la cual se extrajo producción.
- **Producción (t):** Volumen cosechado en toneladas métricas.
- **Rendimiento (t/ha):** Toneladas producidas por hectárea cosechada.
- **Año:** Periodo de registro.

### Conclusiones

El análisis de la distribución y producción agrícola en Costa Rica, fundamentado en los registros oficiales del MAG/SEPSA, permite extraer las siguientes conclusiones principales:

* **Polarización y vocación del uso del suelo:** La estructura agraria del país muestra una marcada polarización territorial. Los grandes agregados agroindustriales y frutícolas lideran ampliamente la extensión sembrada, superando las 100,000 hectáreas, seguidos por cultivos comerciales y de exportación tradicionales como el café, la palma aceitera, la caña de azúcar, la piña y el banano. En contraparte, los cultivos destinados a la dieta básica (granos y hortalizas) ocupan extensiones considerablemente menores, lo que evidencia una orientación predominante del suelo nacional hacia la agroexportación y la producción a gran escala frente a la seguridad alimentaria interna.

* **Desajuste entre superficie y rendimiento volumétrico:** El diagrama de dispersión demostró que no existe una relación estrictamente lineal y proporcional entre el área sembrada y el volumen físico cosechado. Cultivos de extensión moderada pero con alta densidad de biomasa o industrialización masiva —como la caña de azúcar y las frutas frescas— generan volúmenes de toneladas métricas muy superiores en comparación con cultivos de enorme superficie territorial como el café. Esto refleja que la eficiencia productiva y el peso del producto varían drásticamente según las características fisiológicas y de procesamiento de cada especie.

* **Dinamización y contracción histórica de los cultivos tradicionales:** La serie temporal de la producción cafetalera entre 1987 y 2023 evidencia una tendencia general decreciente y de alta volatilidad[cite: 18]. Mientras que en las décadas de 1980 y 1990 el país consolidaba producciones que superaban habitualmente las 800,000 toneladas[cite: 18], el sector ha enfrentado una contracción sostenida que estabiliza la producción reciente por debajo de las 500,000 toneladas[cite: 18]. Esta reducción ilustra la vulnerabilidad de los cultivos tradicionales ante factores socioeconómicos, fluctuaciones de los mercados internacionales y presiones ambientales o fitosanitarias a lo largo del tiempo.

### Referencias Bibliográficas y Fuentes de Datos

* **Ministerio de Agricultura y Ganadería (MAG) & Secretaría Ejecutiva de Planificación Sectorial Agropecuaria (SEPSA).** (2026). *Costa Rica: Extensión sembrada y producción de las principales actividades agrícolas (hectáreas y toneladas métricas)* [Archivo de Excel]. Sistema de Información del Sector Agropecuario Costarricense (InfoAgro). Disponible en: [https://sepsa.mag.go.cr/](https://sepsa.mag.go.cr/)

* **Instituto Nacional de Estadística y Censos (INEC).** (2024). *Encuesta Nacional Agropecuaria 2024: Cultivos anuales por área sembrada, área cosechada, producción y destino de la producción* [Archivo de Excel y base de datos]. Área de Estadísticas Continuas, INEC, Costa Rica. Disponible en: [https://inec.cr/](https://inec.cr/)

Para el trabajo se hizo uso de la IA para la elaboración del codigo. 
