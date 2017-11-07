> ## Si llego buscando el archivo de instalación para su tienda [Descargue la última versión dando click Aquí] [compropago-2-0-x]

Plugin para PrestaShop ( 1.6.1.x + ) - ComproPago 
=================================================
## Descripción
Este modulo provee el servicio de ComproPago para poder generar intenciones de pago dentro de la plataforma PrestaShop. 

Con ComproPago puede recibir pagos en OXXO, 7Eleven y muchas tiendas más en todo México.

[Registrarse en ComproPago ](https://compropago.com)

## Ayuda y Soporte de ComproPago

- [Centro de ayuda y soporte](https://compropago.com/ayuda-y-soporte)
- [Solicitar Integración](https://compropago.com/integracion)
- [Guía para Empezar a usar ComproPago](https://compropago.com/ayuda-y-soporte/como-comenzar-a-usar-compropago)
- [Información de Contacto](https://compropago.com/contacto)

## Requerimientos
* [PrestaShop 1.6.1.15, 1.6.1.16 o 1.6.1.17](https://www.prestashop.com/)
* [PHP >= 5.5](http://www.php.net/)
* [PHP JSON extension](http://php.net/manual/en/book.json.php)
* [PHP cURL extension](http://php.net/manual/en/book.curl.php)

**Nota.-Este plugin sólo funcionará con cuentas de ComproPago generadas a partir de Agosto del 2017. Si tienes una cuenta creada anteior a esta fecha por favor utilizar la versión 2.2.2.3 del plugin.**

## Instalación

1. Comprimir el directorio "compropago" en formato .zip y subirlo por el manejador de modulos de PrestaShop. Si prefiere la opción vía FTP deberá subir el directorio "compropago" al directorio "modules" ubicado en el directorio raiz de PrestaShop
	
2. En la administración de Prestashop (backoffice) ir a: **Módulos > Módulos** y buscar el nombre del módulo: **compropago** y dar click en "Instalar". Una vez instlado recibirá el siguiente mensaje: " Módulo(s) instalado correctamente."<br />

3. Agregar las llaves, ir al panel de administración de ComproPago (https://compropago.com/panel/configuracion), copiar y pegar las llaves, dentro de las configuraciones del modulo en el panel de administración de PrestaShop (backoffice)

4. Una vez ingresadas las llaves se puede proceder a la configuración del Webhook, quien será responsable de actualizar el estado de las ordenes de compra en automatico. 

## Documentación
### Documentación ComproPago Plugin Prestashop

### Documentación de ComproPago
**[API de ComproPago] (https://compropago.com/documentacion/api)**

ComproPago te ofrece un API tipo REST para integrar pagos en efectivo en tu comercio electrónico o tus aplicaciones.


**[General] (https://compropago.com/documentacion)**

Información de Comisiones y Horarios, como Transferir tu dinero y la Seguridad que proporciona ComproPAgo


**[Herramientas] (https://compropago.com/documentacion/boton-pago)**
* Botón de pago
* Modo de pruebas/activo
* WebHooks
* Librerías y Plugins
* Shopify

## Configuración Webhook

1. Ir al area de Webhooks dentro del panel de administración de ComproPago (https://compropago.com/panel/webhooks)

2. Agregar una dirección Webhook e ingresar: <b> [direcciondetienda.com]</b>/modules/compropago/webhook.php cambiando "[direcciondetienda.com]" por el nombre de dominio de su tienda

3. Una vez agregada la dirección, dar click en el botón "Probar", recibira un mensaje similar a "Pruebas: El webhook esta correctamente instalado." con este mensaje la instalación queda completada.


## Guía de Versiones

| Version | Status      |  PrestaShop   | PHP     | Archivo                    | 
|---------|-------------|---------------|---------|----------------------------|
| 1.0.0   | EOL		| 1.5.x a 1.6.0 | 5.2 +   | [v1.0.0][compropago-1-0-0] |
| 2.0.2   | EOL      | 1.6.1.x + 	| 5.4 +   | [v2.0.2][compropago-2-0-2] |
| 2.0.x   | Latest      | 1.6.1.x + 	| 5.5 +   | [v2.0.x][compropago-2-0-x] |



[compropago-2-0-x]: https://s3.amazonaws.com/compropago/plugins/prestashop/compropago-ps-2-0-x.zip
[compropago-2-0-2]: https://s3.amazonaws.com/compropago/plugins/prestashop/compropago-ps-2-0-2.zip
[compropago-1-0-0]: https://s3.amazonaws.com/compropago/plugins/prestashop/compropago-ps-1-0-0.zip
