# 🏠 House-Price

**Price-House** es un proyecto de análisis inmobiliario desarrollado en **Qlik Sense**, que tiene como objetivo explorar el comportamiento de precios, características estructurales y condiciones de propiedades residenciales a partir de un conjunto de datos estructurados.
---

## 📸 Vista previa del dashboard

Podés ver el Dashboard haciendo click en la imagen JPG de los archivos.
https://github.com/Salinas-Javier/Qlik_House_Price/blob/main/House_Price.jpg
---

## 📊 Objetivo del proyecto

Analizar cómo varían los precios de las viviendas en función de variables clave como:
- Superficie (Area)
- Dormitorios y baños
- Condición de la propiedad
- Zona geográfica (Location)
- Presencia de garage
- Antigüedad (a partir de `YearBuilt`)

---

## ⚙️ Herramientas utilizadas

- **Qlik Sense Desktop** (visualización e inteligencia de datos)
- **Qlik scripting** (transformación de datos)
- **Gráficos de dispersión, barras, KPI y tortas** para análisis interactivo

---

## 🧮 Variables analizadas

| Campo        | Descripción                             |
|--------------|------------------------------------------|
| `Area`       | Superficie total de la propiedad         |
| `Bedrooms`   | Cantidad de habitaciones                 |
| `Bathrooms`  | Cantidad de baños                        |
| `Floors`     | Cantidad de pisos                        |
| `YearBuilt`  | Año de construcción                      |
| `Location`   | Ubicación geográfica                     |
| `Condition`  | Estado general de la propiedad           |
| `Garage`     | Si posee o no garage                     |
| `Price`      | Precio de publicación de la propiedad    |

---

## 📈 Visualizaciones principales

- **KPI Cards**: Precio promedio, cantidad total de propiedades
- **Gráfico de dispersión**: Área vs Precio por propiedad
- **Gráfico de barras**:
  - Precio promedio por cantidad de habitaciones
  - Precio promedio por estado de condición
  - Precio promedio según presencia de garage
- **Gráfico circular**: Distribución de propiedades por zona
- **Análisis por m²**: Precio promedio por m² por zona

---

## 🔍 Principales hallazgos

- Las propiedades ubicadas en zonas suburbanas tienden a tener precios promedio más altos, incluso sin ser las más grandes en superficie.
- El centro (Downtown) ofrece propiedades con mayor área promedio, pero a un precio promedio más bajo que Suburban.
- Urban es la zona más económica, tanto en precio como en tamaño.
- La condición de la propiedad tiene un impacto significativo en el precio final.

---

## 🚀 Cómo usar este proyecto

1. Cloná este repositorio:
   ```bash
   git clone https://github.com/tu_usuario/Price-House.git

## 🚀 Ingresá a Qlik

Abrí Qlik Sense Desktop y cargá el archivo .qvf incluido (si lo publicás).

Verificá el script de carga para ajustar rutas si es necesario.

Interactuá con el dashboard y descubrí insights.


  
