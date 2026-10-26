<div align="center">

# Komma POS Retail

**El punto de venta para tiendas, desde el escritorio**

Cobra en segundos con lector de códigos de barras, controla el stock de cada
tienda, gestiona devoluciones, vales regalo y campañas de descuento, cierra la
caja con el efectivo contado y factura con Verifactu. Funciona sin conexión.

Un producto de **Komma SoftHouse**.

[**⬇ Descargar la última versión**](https://github.com/komma-softhouse/komma-pos-retail-releases/releases/latest)

</div>

---

## Descargas

Descarga el instalador para tu sistema operativo desde la
[**última versión**](https://github.com/komma-softhouse/komma-pos-retail-releases/releases/latest).

| Sistema                   | Archivo       | Notas                                         |
| ------------------------- | ------------- | --------------------------------------------- |
| **Windows**               | `…-setup.exe` | Instalador. Doble clic y seguir el asistente. |
| **macOS (Apple Silicon)** | `…-arm64.dmg` | Para Mac con chip M1/M2/M3/M4.                |
| **macOS (Intel)**         | `…-x64.dmg`   | Para Mac con procesador Intel.                |

> ¿No sabes cuál elegir? En Windows descarga el `.exe`; en un Mac moderno el
> `.dmg` **arm64**; en Mac antiguo el `.dmg` **x64**.

---

## Instalación

### Windows
1. Descarga el archivo `…-setup.exe`.
2. Ábrelo y sigue el asistente.
3. Si Windows muestra un aviso de **"editor desconocido"** (SmartScreen),
   pulsa **Más información → Ejecutar de todos modos**. La aplicación es segura;
   el aviso aparece porque el instalador aún no está firmado con certificado de Windows.

### macOS
1. Descarga el `.dmg` correspondiente a tu Mac (arm64 o x64).
2. Ábrelo y arrastra **Komma POS Retail** a la carpeta **Aplicaciones**.
3. Ábrelo desde Aplicaciones. La aplicación está firmada y notarizada por Apple.
4. Si aun así macOS muestra **"la aplicación está dañada"**, abre **Terminal** y ejecuta:
   ```bash
   xattr -rd com.apple.quarantine "/Applications/Komma POS Retail.app"
   ```
   Solo hace falta en la primera instalación; las actualizaciones automáticas no lo requieren.

---

## Actualizaciones automáticas

La aplicación **se actualiza sola**. Al abrirla, comprueba si hay una versión nueva,
la descarga en segundo plano y la aplica al reiniciar. También puedes comprobar
actualizaciones manualmente desde la **pantalla de inicio → Buscar actualizaciones**.

No necesitas volver a descargar nada manualmente salvo en la primera instalación.

---

## Primeros pasos

La pantalla de inicio te guía en la primera puesta en marcha:

1. Introduce tu **clave de licencia** para activar este ordenador.
2. **Crea tu negocio**: nombre y NIF, la primera tienda con su serie de tickets
   y la cuenta del administrador.
3. En **Administración**, da de alta tus productos (con variantes y códigos de barras)
   y a tus empleados, cada uno con su **PIN** de caja.
4. Configura la impresora térmica en **Administración → Tiendas** (red, USB o impresora de Windows).
5. Pulsa **Ir a la caja**, entra con tu PIN, abre la caja y empieza a vender.

En la caja puedes elegir **pantalla táctil** o **teclado y ratón** para cada
ordenador, desde el menú de usuario.

---

## Soporte

¿Problemas con la instalación, la licencia o el uso de la aplicación?
Contacta con **Komma SoftHouse**.

- Web: https://kommasofthouse.com
- Soporte: info@kommasofthouse.com

También puedes enviarnos una incidencia desde la propia caja, con
**Reportar un problema** en el menú de usuario.

---

<div align="center">

© Komma SoftHouse. Todos los derechos reservados.

Este repositorio contiene únicamente los instaladores publicados.
El código fuente es privado y propiedad de Komma SoftHouse.

</div>