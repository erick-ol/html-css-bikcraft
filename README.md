## Bikcraft website

---

This was a project developed with the [Origamid Course (HTML e CSS para Iniciantes)](https://www.origamid.com/curso/html-e-css-para-iniciantes/) with all basis from HTML5, CSS3 and JS (and a few PHP to send emails). Made on `December 5th, 2022`.

### How to download and run the project code

First of all you need to download the project files, you can do this using git.

```bash
git clone git@github.com:erick-ol/html-css-bikcraft.git
```

After you clone the repository you need to enter the folder that contains the project so you can finish all the setups. To use the mail feature you need to clone PHPMailer repository and config the credentials for your e-mail.

```bash
# Cloning and deleting the .git folder so it coudn't cause any conflicts
git clone git@github.com:PHPMailer/PHPMailer.git
rm -rf PHPMailer/.git

# Copying enviar.php file to config the credentials
cp enviar.php.example enviar.php
```

Enter now the `enviar.php` file and set your email and password to use the mailer feature.

Then you just need to open your `index.html` file on the browser.

---

### Images from the project

<details>
  <summary>
    <strong>All images from the project</strong>
  </summary>
</details>
