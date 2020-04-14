# labview
<br>
Exercícios feitos enquanto estudava para o curso da Udemy: LabVIEW & Arduino <br>

## Versão: <br>
LabVIEW 2018 <br>

## Atalhos: <br>
CTRL + T -> divide a tela <br>
ctrl + H -> context help <br>
ctrl + space -> quick drop <br>

## Observação: <br>
É necessário utilizar essas informações para poder usar na pasta email (caso seu email seja gmail): <br>
outgoing mail SMTP: smtp.gmail.com <br>
port: 587 <br>
use TLS: change to true <br> 
username = your email <br> 

### Lembre-se de ativar o POP/IMAP (em configurações -> Encaminhamento e POP/IMAP) e ativar email menos seguros (Gerenciar sua Conta do Google -> Segurança -> Acesso a app menos seguro) no gmail. <br> 

### É necessário abrir o arquivo .vi, clique na seta para direita (Run) no painel frontal para executar o programa.  <br>

## Descrição sobre cada programa: <br>
### labview/email/: 
## controle_temperatura_email.vi ->
Quando a temperatura passa do limite escolhido pelo usuário (no controle Dial), é enviado um email avisando que a temperatura está fora do controle e o programa termina (preencher os campos que estão faltando para o email ser enviado no block diagram). <br>

## email.vi ->
O usuário deve digitar outgoing mail SMTP, Port (porta), To (para quem quer mandar), From (enviado por quem), username (= seu email - from), password (senha do email), ative use TLS (false) para true - clique para aparecer a cor verde claro de aceso, subject (assunto), plain text message (mensagem). Clique em Run e o email será enviado. <br>

### labview/exercicio_14_arquivos/:
## write_randoms.vi e read_randoms.vi -> 
Para o programa write_randoms, o usuário para escrever deve escolher o arquivo .txt em file path (use dialog), em seguida o programa retornará na parte string e escreverá no arquivo um número randômico com precisão de 2 casas decimais seguido da data e do horário que foi escrito. Para o programa read_randoms, o usuário deve escolher o arquivo .txt que deseja ler em file path (use dialog) e clicar no botão ler, na parte string irá aparecer o que será lido. Para terminar o programa clique no botão STOP. <br>


## write_other_randoms.vi e read_other_randoms.vi -> 
Para o programa write_other_randoms, o usuário deve executar o programa, logo em seguida será mostrado um gráfico com 100 números aleatórios gerados. Inicialmente o número 1000 é dividido por i = 1 e multiplicado por um número randômico, nas próximas iterações, o valor guardado é sempre dividido por i e depois multiplicado por um número randômico. Para o programa read_other_randoms, os 100 números guardados e gerados a partir do write_other_randoms são mostrados em um gráfico ao executar o programa. <br>

### labview/dui/:
dui = paleta dialog & user interface <br>
## exercicios12_dui.vi -> <br> 
Exercício 1: 15 números randômicos gerados em um gráfico quando o usuário clica no botão Gerar. Se o usuário clicar no botão Finalizar, irá aparecer uma caixa de mensagem perguntando se ele deseja finalizar a execução. Caso a resposta seja Sim, o programa finalizará. Caso a resposta seja Não, o programa continuará aberto. <br>
Exercício 2: O usuário deve digitar o Nome, Número, Mensagem e clicar em Enviar. Logo em seguida, aparecerá quantos caracteres deu a mensagem e aparecerá uma janela com as informações digitadas. <br> <br>
## dui.vi -> 
Exercícios feitos enquanto assistia a aula, irá aparecer várias mensagens na tela quando o usuário executar o programa.
<br>
Essa é uma mensagem de teste!: Se clicar em Sair, o led true acende e a mensagem fecha. <br>
Mensagem!: Pode clicar em Iniciar ou Cancelar, T button? acende para Iniciar e apaga para Cancelar <br>
Essa é uma mensagem de texto! Which Button? irá dizer qual opção foi escolhida em Center, Left, Right Button, se a resposta for Sim, Não, Cancelar. <br>
Erro de Processamento: Aparece a mensagem "Erro de processamento, feche a aplicação." Clicando em OK ou Cancelar, a mensagem fecha. <br>
Salvar Arquivo?: Se sim, aparece outra mensagem dizendo Documento Salvo!, Caso Não: o programa fica em looping perguntando se deseja salvar arquivo. <br>
Ok Button: Clicando em um dos três botões, aparecem diferentes mensagens: Iniciado, Dados, Salvo. E o led true 2, 3 e 4 acende dependendo de qual botão for clicado. <br>



<br>



### labview/:
## relogio.vi -> 
O usuário precisa escolher um horário para começar a contar as horas. Quando ele clicar em "Definir", o relógio começa a contar os segundos, minutos e horas (Um led fica piscando para mostrar que o tempo está sendo contado a partir daquele momento definido pelo usuário). <br>

## led_piscando.vi ->
Quando o programa é executado, os 3 leds ficam piscando na cor azul. <br>

## exercicios8_despertador.vi -> 
O usuário precisa digitar um horário para o despertador tocar (No Campo Hora 24h, Minutos). Quando é apertado o botão "Definir", o relógio mostra a hora atual. No momento que der o horário escolhido, o led irá acender. <br> 



