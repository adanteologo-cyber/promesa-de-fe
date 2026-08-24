# Promesa de Fe

Formularios HTML autocontenidos para que la Iglesia Cristiana Jerusalén registre promesas de fe y compromisos misioneros de sus miembros. No requieren servidor ni instalación: se abren directamente en el navegador.

## Archivos

- **`index.html`** — Tarjeta de compromiso de fidelidad (diezmos, ofrendas, misiones, construcción).
- **`promesa-fe-misionera.html`** — Registro de promesas de fe misionera, con monto y duración del compromiso.
- **`registro.html`** — Página de bienvenida con enlace a un Google Form y datos de transferencia bancaria para quienes prefieran registrar su promesa así.

## Uso

Abre cualquiera de los archivos `.html` directamente en un navegador. Los registros se guardan localmente en el navegador (`localStorage`) y pueden exportarse a CSV desde el botón correspondiente en cada formulario.

### Configurar el Google Form en `registro.html`

Edita `registro.html` y reemplaza el valor de `GOOGLE_FORM_URL` con el enlace de tu formulario:

```js
const GOOGLE_FORM_URL = "https://forms.gle/xxxxxxxxxxxx";
```
