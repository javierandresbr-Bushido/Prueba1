# Prueba1: este archivo se usa para almacenar una base de datos de vuelos

# Metadata del Archivo de Vuelos

| Atributo / Columna | Detalle | Tipo de Dato | No Nulos | Observaciones |
| :--- | :--- | :--- | :--- | :--- |
| **Archivo** | `Vuelo,Tipo Aeronave,Pasajeros,Estad.csv` | - | - | Contiene 100 filas y 4 columnas |
| **Vuelo** | Identificador de la aeronave | Texto (Object) | 100/100 | 92 códigos únicos (ej. HK4521) |
| **Tipo Aeronave** | Categoría del avión | Texto (Object) | 100/100 | 5 tipos (Comercial, Carga, JR, etc.) |
| **Pasajeros** | Cantidad de personas | Entero (Int64) | 100/100 | Rango: 0 - 175 (Promedio: 56.19) |
| **Estado** | Situación operativa | Texto (Object) | 100/100 | 5 estados (ej. En plataforma, En rodaje) |
