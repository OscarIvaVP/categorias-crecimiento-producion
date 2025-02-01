# **Determinación del Crecimiento de Producción por Cuenca**

## **Descripción del Proyecto**
Este proyecto tiene como objetivo la determinación del crecimiento histórico de producción agrícola y pecuaria a nivel de cuenca hidrográfica a partir de datos municipales. Se emplean técnicas de modelado de crecimiento y análisis de umbrales para categorizar la evolución de la producción.

## **Estructura del Código**
El código está organizado en las siguientes secciones:

1. **Importación de Librerías**: Se importan las librerías necesarias para la manipulación de datos y visualización.
2. **Carga de Datos**: Se leen los archivos Excel que contienen datos históricos de producción agrícola y pecuaria, junto con proporciones de distribución por cuenca.
3. **Procesamiento de Datos**:
   - Transformación de datos municipales a nivel de cuenca mediante proporciones asignadas.
   - Cálculo de hectáreas por cuenca y año.
   - Almacenamiento de resultados en archivos de salida.
4. **Cálculo de Crecimiento**:
   - Cálculo de la tasa de crecimiento anual para cada cuenca y tipo de producción.
   - Generación de gráficos de crecimiento por cuenca y cultivo.
5. **Establecimiento de Umbrales de Crecimiento**:
   - Determinación de cuartiles para categorizar el crecimiento en bajo, medio y alto.
   - Creación de diagramas de caja para cada cuenca y cultivo.
   - Generación de archivos con los valores de los umbrales de crecimiento.
6. **Visualización**:
   - Gráficos de crecimiento anual.
   - Diagramas de caja para umbrales de crecimiento.

## **Requisitos**
Para ejecutar este proyecto se necesita:
- Python 3.7+
- Librerías:
  - `pandas`
  - `numpy`
  - `matplotlib`
- Google Colab (opcional, si se usa almacenamiento en Google Drive)

## **Ejecución del Proyecto**
1. Montar Google Drive si se ejecuta en Google Colab.
2. Asegurarse de que los archivos de entrada están correctamente almacenados en las rutas especificadas.
3. Ejecutar las celdas en orden para procesar los datos y calcular tasas de crecimiento.
4. Analizar los resultados generados en los archivos de salida y gráficos.

## **Archivos de Entrada**
- `proporcion.xlsx`
- `historico-arroz.xlsx`
- `historico-cacao.xlsx`
- `historico-ganaderia.xlsx`
- `historico-palma.xlsx`
- `proporcion-urbano.xlsx`
- `proporcion-rural.xlsx`

## **Archivos de Salida**
- `ganaderia-historico-cuencas.xlsx` → Datos históricos transformados a nivel de cuenca.
- `datos-unidos-cuencas.xlsx` → Datos consolidados de todas las cuencas y cultivos.
- `crecimiento-anual-cuencas.xlsx` → Tasas de crecimiento anual por cuenca y cultivo.
- `umbrales_crecimiento.xlsx` → Umbrales de crecimiento bajo, medio y alto.

## **Contacto**
Para cualquier consulta o colaboración, por favor contacta a través de este repositorio o a [oscarvargas@trabajocientific.com].

