# plugin-whmcs-agregador
**Si usted tiene alguna pregunta o problema, no dude en ponerse en contacto con nuestro soporte técnico: desarrollo@payco.co.**


## Versiones

## Versiones
* [ePayco plugin WHMCS v8.0.0](https://github.com/epayco/plugin-whmcs-agregador/releases/tag/v8.0.0).
* [ePayco plugin WHMCS v7.10.x](https://github.com/epayco/plugin-whmcs-agregador/releases/tag/v7.10.x).


### Installing


1- Clonar el repositorio en su máquina de acuerdo a la versión de WHCMS.

```
git clone https://github.com/epayco/plugin-whmcs-agregador
```
2- Ingresar a la carpeta creada y copiar el contenido en su instalación de whmcs en la ruta raíz de la tienda  ruta/de/su/instalacion/whmcs/
```
cd payco_whmcs
cp . -R /ruta/de/su/instalacion/whmcs/
```
3- Dirigirse a la ruta de instalación de su whmcs ruta/de/su/instalacion/whmcs/modules/gateways/ y asegurarse que los archivos descargados se encuentren en la ruta correspondiente
```
* ruta/de/su/instalacion/whmcs/modules/gateways/epaycoagregador.php
* ruta/de/su/instalacion/whmcs/modules/gateways/epayco/epaycoagregador.php
* ruta/de/su/instalacion/whmcs/modules/gateways/callback/epaycoagregador.php
```

## Finalización

Ya puede ingresar al área de administración de whmcs e ingresar a ajustes->Pasarelas de pago y encontrará el panel de ePayco agregador para configurarlo.