---
layout: default
title: Privacidad
lang: es-419
home_path: /es/
support_path: /es/support/
privacy_path: /es/privacy/
terms_path: /es/terms/
permalink: /es/privacy/
---

# Política de privacidad de Gantt Chart for Sheets

**Última actualización: 14 de octubre de 2026**

## Resumen

Este complemento no tiene permiso para acceder a Internet. Lee la lista de tareas, la convierte en un diagrama de Gantt y lo escribe en una pestaña de la misma hoja de cálculo. No recopilamos, almacenamos, vendemos ni compartimos datos personales mediante el complemento.

## A qué puede acceder el complemento

Solicita exactamente estos dos permisos:

| Permiso | Alcance | Uso |
|---|---|---|
| Ver, editar, crear y eliminar solo el archivo de Google Sheets que estás usando | `spreadsheets.currentonly` | Leer las tareas y escribir el gráfico en otra pestaña del mismo archivo |
| Mostrar y ejecutar contenido web en mensajes y barras laterales | `script.container.ui` | Mostrar el menú y los cuadros de diálogo del complemento |

Google añade tu nombre y correo electrónico a la pantalla de instalación de Google Workspace Marketplace. Es un requisito para todos los complementos publicados. El código del complemento no lee esos datos; tampoco los recibimos ni almacenamos.

El complemento no accede a Google Drive, a otras hojas de cálculo, al correo, los contactos ni el calendario. Tampoco tiene el permiso `script.external_request`, por lo que no puede conectarse a redes externas.

## Qué se guarda y dónde

El almacenamiento de complementos de Google dentro de tu cuenta guarda:

1. Tus preferencias por hoja de cálculo: excluir fines de semana y resaltar la ruta crítica.
2. Tu clave de licencia, si tienes una. Puede contener el plan, la fecha de vencimiento y la referencia de compra; no contiene tu nombre ni tu correo electrónico.

Al desinstalar el complemento, Google elimina estos datos. También puedes borrar la clave cuando quieras: abre **Extensiones → Gantt Chart for Sheets → Licencia**, deja el campo vacío y confirma.

## Datos que recibimos cuando compras una licencia

El proveedor de pagos, no el complemento, procesa las compras. Al comprar Pro, recibimos una referencia de pedido y el correo electrónico al que debemos enviar la clave. Nunca vemos ni almacenamos los datos de tu tarjeta. Un pequeño script de Google Apps Script genera y envía la clave; la referencia y el correo se guardan en el almacenamiento privado de nuestra cuenta.

Solo usamos estos datos para emitir o reenviar la clave y conservar los registros exigidos por ley. No los usamos para marketing ni los compartimos con terceros. Los conservamos durante el plazo exigido por la normativa fiscal y los eliminamos después. Puedes solicitar que se borren antes cuando la ley lo permita.

## Cómo protegemos tus datos

**Durante la transmisión:** Los datos de la hoja nunca salen de la infraestructura de Google. El complemento se ejecuta como Google Apps Script y escribe el gráfico en el mismo archivo. Google protege con TLS las conexiones entre el navegador y el script. El complemento no tiene permiso de red externa.

**Almacenamiento:** No conservamos copias de los datos de la hoja. Los nombres de tareas, fechas y responsables solo se procesan en memoria mientras se genera el gráfico. Las preferencias y la clave, si existe, se guardan en `PropertiesService` de Google, cifrado por Google en reposo. No podemos leer esos valores.

**Control de acceso:** No existe una vía para que Slowgrain acceda a los datos de tu hoja. No hay empleados, contratistas ni procesadores con acceso a ellos. El proyecto de Apps Script publicado pertenece a una sola cuenta de Google. El secreto que firma las claves no se confirma en el repositorio ni se incluye en el código publicado.

## Conservación y eliminación

- No conservamos los datos de las hojas de cálculo.
- Google elimina tus preferencias y la clave al desinstalar el complemento; también puedes borrar la clave manualmente.
- Conservamos la referencia del pedido y el correo solo durante el plazo fiscal obligatorio y los eliminamos al terminar. Puedes contactar con nosotros para solicitar su eliminación anticipada cuando la ley lo permita.

El gráfico se escribe en una pestaña de tu hoja y hereda la configuración para compartir ese archivo. Quienes ya tengan acceso al archivo podrán ver el gráfico igual que la lista original. Nosotros no publicamos ni compartimos el gráfico.

## API de Google Workspace e IA

No usamos datos de Google Workspace API para desarrollar, mejorar ni entrenar modelos de IA o aprendizaje automático, generales o no personalizados. El complemento no usa IA ni aprendizaje automático; calcula los calendarios con operaciones normales.

El uso y la transferencia de información recibida de las API de Google cumplen la [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), incluidos sus requisitos de uso limitado.

## Menores

Este complemento es una herramienta de trabajo y no está dirigido a menores de 13 años.

## Cambios

Si cambia esta política, actualizaremos la fecha y publicaremos la versión vigente en esta dirección.

## Contacto

Para consultas sobre privacidad o solicitudes de eliminación de información:

**slowgrain.dev@gmail.com**

Respondemos en un plazo de cinco días laborables.
