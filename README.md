# StoQuito 1.0.0

**StoQuito** es una aplicación de escritorio para controlar el inventario de pequeños negocios y bodegas. Permite saber qué productos hay, cuántas unidades quedan y cuándo ingresaron o salieron, sin depender de hojas de cálculo ni de una conexión a Internet. Funciona en una sola PC con Windows 10 u 11 de 64 bits y guarda la información localmente.

Su descarga, instalación y uso son gratuitos, incluso para gestionar un negocio.

## ¿Qué puedes hacer con StoQuito?

- **Organizar productos:** registrar códigos, nombres, categorías, proveedores, precios, existencias mínimas e imágenes; buscar y filtrar el catálogo.
- **Controlar el stock:** registrar entradas, salidas y ajustes autorizados. El sistema actualiza las existencias y evita las salidas que dejarían el stock negativo.
- **Consultar el historial:** revisar cuándo se movió cada producto, en qué cantidad y qué usuario realizó la operación.
- **Detectar faltantes:** ver productos con bajo stock y consultar indicadores en el Dashboard, con filtros por fechas.
- **Exportar información:** descargar el inventario filtrado en CSV o Excel (`.xlsx`).
- **Proteger los datos:** crear respaldos manuales, con la opción de incluir imágenes, y restaurarlos cuando sea necesario. No se hacen respaldos automáticos.
- **Trabajar con permisos:** usar cuentas con roles de Administrador, Operador o Consulta.

StoQuito está enfocado en inventario: **no es un sistema de ventas, facturación ni gestión de clientes**.

## Cómo empezar

1. Descarga e instala la aplicación desde la sección siguiente. El instalador incluye .NET; no necesitas instalarlo por separado.
2. Inicia sesión con el usuario inicial `admin` y la contraseña temporal `admin123`. En el primer acceso deberás cambiarla.
3. Crea una **categoría** y, si lo necesitas, un **proveedor**.
4. Crea los **productos** dentro de su categoría. Los productos nuevos comienzan con stock cero.
5. Registra una **entrada** para cargar las existencias iniciales. Después, registra cada entrada o salida para mantener el stock y el historial correctos.
6. Revisa el Dashboard y crea un **respaldo manual** de forma periódica, especialmente antes de cambios importantes.

La [guía de uso en PDF](https://github.com/ElHendri87/StoQuito-app/releases/download/v1.0.0/GUIA_DE_USO.pdf) explica paso a paso estas tareas, la administración de usuarios y la restauración de respaldos para los tres roles.

## Descargar la versión 1.0.0

- [Descargar el instalador de StoQuito (`.exe`)](https://github.com/ElHendri87/StoQuito-app/releases/download/v1.0.0/StoQuito-Setup-1.0.0.exe)
- [Descargar la guía de uso (`.pdf`)](https://github.com/ElHendri87/StoQuito-app/releases/download/v1.0.0/GUIA_DE_USO.pdf)

También puedes consultar la [última versión publicada](https://github.com/ElHendri87/StoQuito-app/releases/latest). En GitHub, los archivos automáticos **Source code (zip)** y **Source code (tar.gz)** no son el instalador: descarga el `.exe` de **Assets**. Lee la licencia que aparece durante la instalación.

## Usuarios y datos

El **Administrador** configura el sistema, gestiona usuarios y respaldos y puede realizar ajustes de inventario. El **Operador** trabaja con productos y movimientos de entrada y salida. El rol de **Consulta** solo puede revisar la información. La guía detalla los permisos de cada uno.

Los datos se guardan en el equipo, en `%LocalAppData%\StoQuito\`. Conserva una copia de tus respaldos en un lugar seguro. Para restaurar un respaldo, la aplicación reemplaza los datos actuales por los de esa copia.

## Verificar los archivos descargados

SHA-256 del instalador:

```text
AB0D680D318252C634312854108A653CA0764D4D01A7017269461BA15EE5E0E5
```

SHA-256 de la guía:

```text
CAD956C307B4AA83813C2BD7E3D8CAA0A88C83843AABEC368E6170F1F204DDB1
```

Desarrollado por **El Hendri** · [elhendri.com](https://elhendri.com)
