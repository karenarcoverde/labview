# labview
<br>
LabVIEW 2018 <br>

Atalhos:<br>
CTRL + T -> divide a tela <br>
ctrl + H -> context help <br>
ctrl + space -> quick drop <br>

É necessário utilizar essas informações para poder usar na pasta email: <br>
outgoing mail SMTP: smtp.gmail.com <br>
port: 587 <br>
use TLS: change to true <br> 
username = your email <br> 

É necessário abrir o arquivo .vi, clique na seta para direita (Run) no painel frontal para executar o programa.  <br>

controle_temperatura_email.vi -> Quando a temperatura passa do limite escolhido pelo usuário (no controle Dial), é enviado um email avisando que a temperatura está fora do controle e o programa termina (preencher os campos que estão faltando para o email ser enviado no block diagram). <br>

email.vi -> O usuário deve digitar outgoing mail SMTP, Port (porta), To (para quem quer mandar), From (enviado por quem), username (= seu email (from)), password (senha do email), ative use TLS (false) para true, subject (assunto), plain text message (mensagem). Clique em Run e o email será enviado. <br>

relogio.vi -> O usuário precisa escolher um horário para começar a contar as horas. Quando ele clicar em "Definir", o relógio começa a contar os segundos, minutos e horas (Um led fica piscando para mostrar que o tempo está sendo contado a partir daquele momento definido pelo usuário). <br>

led_piscando.vi -> Quando o programa é executado, os 3 leds ficam piscando na cor azul. <br>

exercicios8_despertador.vi -> O usuário precisa digitar um horário para o despertador tocar (No Campo Hora 24h, Minutos). Quando é apertado o botão "Definir", o relógio mostra a hora atual. No momento que der o horário escolhido, o led irá acender. <br> 
