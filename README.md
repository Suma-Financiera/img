# Suma Financiera — Repositorio de Imágenes Públicas

Repositorio oficial destinado al almacenamiento y distribución de los recursos gráficos públicos de **Suma Financiera**. Su propósito es centralizar los archivos de imagen (logotipos, banners y demás piezas institucionales) y proveer una URL pública y estable para su consumo desde formularios, correos electrónicos, sitios web y flujos de trabajo corporativos.

## Estructura

```
.
├── banner/   Piezas gráficas de campañas, formularios y comunicaciones
└── logo/     Identidad corporativa (logotipos institucionales)
```

### Contenido actual

| Ruta | Descripción |
| --- | --- |
| `logo/logo-suma.png` | Logotipo institucional de Suma Financiera |
| `banner/solicitud-credito.jpg` | Banner del formulario de solicitud de crédito |
| `banner/consultas-de-estado.jpg` | Banner del formulario de consultas de estado |
| `banner/programa-referidos.jpg` | Banner del programa de referidos |
| `banner/referidos-ejecutivos-externos.jpg` | Banner de referidos para ejecutivos externos |
| `banner/registro-ejecutivos-externos.jpg` | Banner de registro de ejecutivos externos |

## Uso

Los archivos se consumen mediante su URL pública directa:

```
https://raw.githubusercontent.com/Suma-Financiera/img/main/<carpeta>/<archivo>
```

Ejemplo:

```html
<img src="https://raw.githubusercontent.com/Suma-Financiera/img/main/logo/logo-suma.png" alt="Suma Financiera">
```

## Lineamientos

- Utilizar nombres de archivo en minúsculas, sin espacios ni caracteres especiales, separando palabras con guion medio (`kebab-case`).
- Clasificar cada recurso en la carpeta que corresponda a su categoría.
- Optimizar las imágenes antes de publicarlas, con el fin de reducir los tiempos de carga.
- Evitar la modificación de rutas o nombres de archivos ya publicados, dado que pueden encontrarse referenciados en recursos externos.
- No almacenar en este repositorio información confidencial, datos personales ni material de uso interno: **todo su contenido es de acceso público**.

## Contribución

Los cambios se realizan mediante commits descriptivos siguiendo la convención empleada en el historial del repositorio (`feat`, `fix`, etc.), indicando el tipo de recurso afectado.

---

© Suma Financiera. Los recursos aquí contenidos son propiedad de Suma Financiera y su uso está restringido a fines institucionales autorizados.
