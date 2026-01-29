# Diccionario de datos (resumen)

## Tablas principales
### Calendario
- **Propósito:** soporte de filtros temporales (por ejemplo, Mes).
- **Campos clave:** `Mes` (usado como segmentador).

### Eje Urbano
- **Tabla:** `eje_urbano_usuarios_transporte_urbano_guadalajara_enero_junio_2025`
- **Campos/medidas usados en visuales:** Pasajeros, Kilómetros, Ingresos, Transporte (categoría).
- **Indicadores derivados comunes:** ingresos por km, ingresos por pasajero, pasajeros por km.

### Eje Económico
- **Tabla:** `eje_economico`
- **Campos clave:** `Actividad`, `Unidades`
- **Indicadores comunes:** conteo de actividades, % acumulado, unidades por actividad.

### Eje Cultural
- **Tablas:** `eje_cultural_Espacios culturales` y `eje_culturalHabporBilbioteca,Librería, MyTe`
- **Campos clave:** `Tipo_Espacio`, `Cantidad`, indicadores de habitantes/porcentaje.
- **Indicadores comunes:** total de espacios culturales, distribución por tipo, habitantes por indicador.

## Notas
- Este documento resume lo visible desde el reporte. Si cambian las fuentes o el modelo, actualiza este diccionario.

