# Superposición de concentraciones con AERMOD

Proyecto académico desarrollado en colaboración con el Tecnológico de Monterrey para analizar la superposición de concentraciones atmosféricas modeladas con AERMOD.

## Contenido

- `aermod.inp`: archivo de configuración de entrada para AERMOD-PRIME. Configura una fuente lineal, terreno plano y modelación de NOx, entre otros parámetros.
- `TPA_2017-2021_v22112/`: archivos meteorológicos de superficie (`.SFC`) y perfil (`.PFL`) para los años 2017–2021.
- `PLT24ALL_PE.txt`, `PLT24ALL_TP.txt` y archivos `*_Orig.txt`: resultados de AERMOD en formato de texto.
- Archivos `*_Conv.csv` y `Concentracion_total.csv`: resultados tabulares con coordenadas `X`, `Y` y concentraciones.

## Código y reproducibilidad

Esta copia contiene los datos de entrada y resultados, pero no incluye código fuente Python. El script utilizado para sumar las concentraciones no está disponible aquí; se buscará en el computador donde se desarrolló el proyecto.

Por lo tanto, los CSV y archivos de resultados se conservan como productos del análisis, pero no es posible reproducir desde este repositorio el proceso de conversión o suma. Para volver a ejecutar la modelación también se requiere el ejecutable de AERMOD-PRIME y verificar la disponibilidad y configuración de los datos meteorológicos.

## Colaboración

El proyecto se realizó en colaboración con el Tecnológico de Monterrey. La mención describe la colaboración académica y no implica que esta institución respalde o mantenga este repositorio.
