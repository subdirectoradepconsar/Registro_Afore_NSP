# Registro_Afore_NSP

Copia independiente del registro. No solicita teléfono.

## Configuración de la nueva hoja

1. Crear un proyecto propio de Apps Script para este registro. No modificar implementaciones anteriores.
2. Copiar apps-script/Code.gs, ya configurado con la hoja https://docs.google.com/spreadsheets/d/1yaENRlssj-20tr3gtUJi1SqFnaziJ9qsL4Dd7d4qO4o/edit.
3. Usar en la primera pestaña las columnas: Fecha y hora, Nombre, Correo, Género, Año de nacimiento.
4. Implementar como aplicación web y configurar WEBHOOK_URL en index.html con su dirección /exec.

El formulario está desconectado hasta completar estos pasos. El script usa un único openById y un único appendRow; no incluye ningún destino anterior.
