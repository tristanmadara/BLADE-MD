const { Client, MessageMedia } = require('whatsapp-web.js');
const qrcode = require('qrcode-terminal');

const client = new Client();

client.on('qr', (qr) => {
    qrcode.generate(qr, { small: true });
    console.log('QR code généré, scannez-le avec WhatsApp.');
});

client.on('ready', () => {
    console.log('Jace MD Bot est prêt !');

    // 
    const media = MessageMedia.fromFilePath('chemin/vers/')![image](https://github.com/user-attachments/assets/8c97a470-dafe-4006-9451-4eec7a9376ef)
; // Remplacez par le chemin de votre image
    client.sendMessage('numéro_de_destinataire@c.us', media, { caption: 'Voici Luffy ! Jace MD Bot' });
});

client.on('message', message => {
    if (message.body === '!ping') {
        message.reply('Pong !');
    }
});

client.initialize();<p align="center">
  <a href="https://chat.whatsapp.com/ESB8e9HAS2wGlwBvzGYnLx">
    <img alt=Support height="250" src="https://telegra.ph/file/362dd0f0cb45468934804.jpg"> 
    </p>
      <div align="center">
<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Impact&size=50&pause=1000&color=000000&center=true&width=910&height=100&lines=THIS IS+JACE+MD+BOT;MULTI+DEVICE+WHATSAPP+BOT;CREATED+BY+TEAM JACE;PUBLIC+RELEASED+DATE;2023/08/21;." alt="Typing SVG" /></a>
  </p>
