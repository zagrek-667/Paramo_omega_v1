# Páramo Omega

Experiencia inmersiva e interactiva publicada en GitHub Pages. Es un **hub narrativo** que arranca con un video introductorio (`intro.mp4`) y da acceso a cuatro simulaciones conectadas:

- **Páramo Omega** (hub central): historia ramificada sobre una IA que protege un páramo y clasifica a la humanidad como "patógeno crítico".
- **Refugio Zero**: supervivencia por decisiones con recursos (agua, polvo, moral).
- **Archivo Lyra**: terminal de rescate de una operativa atrapada en el Sector 4.
- **Cronos-Axioma**: consola temporal que gestiona una anomalía gravitacional.

Todo vive en un único `index.html` en la raíz del repositorio. Las fuentes, Tailwind y los iconos se cargan desde CDN; no requieren instalación.

## Archivos de medios (subida manual obligatoria)

El código referencia 6 archivos de medios que **no están incluidos** en este repositorio. Debes subirlos **manualmente** a la **raíz del repositorio** desde la web de GitHub:

1. Entra al repositorio en GitHub.
2. Pulsa **"Add file"** → **"Upload files"**.
3. Arrastra los 6 archivos y confirma el commit.

Los nombres deben ser **EXACTOS** (respeta espacios y mayúsculas):

- `intro.mp4`
- `Lamento de Piedra_2.mp3`
- `Tinta de Sal_2.mp3`
- `Binary Waltz_2.mp3`
- `Synthetic Waltz_2.mp3`
- `Cota Catorce_2.mp3`

> Nota: en el HTML los nombres aparecen codificados con `%20` en lugar de espacios (por ejemplo `Lamento%20de%20Piedra_2.mp3`). Esto es correcto y evita errores de rutas con espacios en GitHub. Sube los archivos con su nombre normal (con espacios); no los renombres con `%20`.

### Correspondencia de audio por sección

| Sección | Archivo de audio | Notas |
|---|---|---|
| Páramo Omega (hub) | `Lamento de Piedra_2.mp3` | Atmósfera general del hub |
| Páramo Omega (hub) | `Cota Catorce_2.mp3` | Suena en las escenas *debate lógico*, *diagnóstico de humedad* y *equilibrio alcanzado* |
| Refugio Zero | `Tinta de Sal_2.mp3` | |
| Archivo Lyra | `Binary Waltz_2.mp3` | |
| Cronos-Axioma | `Synthetic Waltz_2.mp3` | |

El video `intro.mp4` se reproduce en la pantalla introductoria antes de entrar al hub.

## Límite de tamaño

La subida de archivos por la web de GitHub tiene un límite de **25 MB por archivo**. Asegúrate de que cada `.mp3` y el `intro.mp4` no superen ese tamaño.

## Publicación

Una vez subidos los medios y habilitado GitHub Pages, la experiencia quedará disponible en:

https://zagrek-667.github.io/Paramo_omega_v1/
