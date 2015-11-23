# cool-php-captcha
Automatically exported from code.google.com/p/cool-php-captcha
El objetivo de este proyecto es la generación de captchas de seguridad básica generando imágenes relativamente amigables para el usuario.

Example
This project provides the SimpleCaptcha class.

The images are similar to google captchas.

Basic example:

session_start();
$captcha = new SimpleCaptcha();
// Change configuration...
//$captcha->wordsFile = null;           // Disable dictionary words
//$captcha->wordsFile = 'words/es.txt'; // Enable spanish words
//$captcha->session_var = 'secretword'; // Change session variable
$captcha->CreateImage();
