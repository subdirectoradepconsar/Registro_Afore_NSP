# Registro_Afore_NSP

Copia independiente del registro. No solicita teléfono.

## Configuración de la nueva hoja

1. Crear un proyecto propio de Apps Script para este registro. No modificar implementaciones anteriores.
2. En apps-script/Code.gs sustituir PEGAR_ID_DE_LA_NUEVA_HOJA_AQUI por el ID de la hoja nueva (el texto entre /d/ y /edit en su URL).
3. Usar en la primera pestaña las columnas: Fecha y hora, Nombre, Correo, Género, Año de nacimiento.
4. Implementar como aplicación web y configurar WEBHOOK_URL en index.html con su dirección /exec.

El formulario está desconectado hasta completar estos pasos. El script usa un único openById y un único appendRow; no incluye ningún destino anterior.
