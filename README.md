# Experiment

Para instalar las dependencias solo hay que hacer

- npm install

corremos el servidor

- node server.js

para cambiar la dirección de correo de gmail

- var smtpTransport = nodemailer.createTransport("SMTP",{
   service: "Gmail",
    auth: {
    user: "direccion gmail",
   pass: "password"
  }
