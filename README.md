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
  
  <img width="1783" alt="image" src="https://user-images.githubusercontent.com/65933231/205782013-9069754f-8379-416d-b928-38353fb5f6d2.png">
  <img width="1778" alt="image" src="https://user-images.githubusercontent.com/65933231/205782187-d2b74d8e-8854-484a-814c-f3af71489894.png">
  <img width="1781" alt="image" src="https://user-images.githubusercontent.com/65933231/205782606-ca03cf1d-af3a-466d-9a6a-e6971a93ef46.png">
  <img width="1782" alt="image" src="https://user-images.githubusercontent.com/65933231/205782333-9b8e1f76-a18f-4599-9409-cbc800a78872.png">
  <img width="1781" alt="image" src="https://user-images.githubusercontent.com/65933231/205782429-e0894f9e-f101-4875-aa0a-f4aa341be15d.png">

</details>
