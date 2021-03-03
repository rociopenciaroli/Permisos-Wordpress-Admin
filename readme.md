## Agregar este código en el archivo .htaccess:

```js
<Files wp-login.php>
Order Deny,Allow
Deny from all
Allow from all
</Files>
