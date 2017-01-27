### Webgunea publiko egin
#### Konfigurazio fitxategia

- Datu-basea eta erabiltzailea sortuta ditugunez, konfigurazio fitxategia eguneratzea falta zaigu.
- Horretarako, **wp-config-sample.php  wp-config.php** bezala berrizendatu eta datuak gehituko ditugu.

```
// ** Ajustes de MySQL. Solicita estos datos a tu proveedor de alojamiento web. ** //
/** El nombre de tu base de datos de WordPress */
define('DB_NAME', 'wordpress');
/** Tu nombre de usuario de MySQL */
define('DB_USER', 'wordpress');
/** Tu contraseña de MySQL */
define('DB_PASSWORD', 'Pasahitza');
/** Host de MySQL (es muy probable que no necesites cambiarlo) */
define('DB_HOST', 'localhost');
/** Codificación de caracteres para la base de datos. */
define('DB_CHARSET', 'utf8');
/** Cotejamiento de la base de datos. No lo modifiques si tienes dudas. */
define('DB_COLLATE', '');
```