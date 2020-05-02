# Lista Angular Mobile - CCP3AN
Ramon Pereira
Abril 2020
1. Prepare o ambiente para a realiza¸c˜ao do exerc´ıcio:
(a) Visual Code: https://code.visualstudio.com/download
(b) NodeJS: https://nodejs.org/en/download/
(c) Angular-CLI: npm install -g @angular/cli
(d) Criar o projeto Aula 1: ng new Aula1
(e) Entrar na pasta cd Aula1
(f) Angular Bootstrap: npm install bootstrap
(g) Adicionar o Bootstrap adicionando a linha: @import 0
bootstrap/dist/css/bootstrap.min.css0
;
no arquivo style.css dentro da pasta src/.
2. Cria¸c˜ao de componentes:
(a) Crie um componente chamado Eventos. (ng generate component
eventos)
(b) O HTML a ser utilizando no componente Eventos sem o Data Binding
est´a dispon´ıvel na pasta de recursos
(c) Adicione uma propriedade no JavaScript do componente Eventos
para receber um evento, este evento est´a salvo no arquivo evento.json
da sua pasta de recursos, basta copiar e coloca-lo na propriedade.
(d) Adicione os data bindings necess´arios usando interpola¸c˜ao para os
dados do evento serem exibidos no componente de template Eventos.
(e) Adicione o componente no template do App Component (<appeventos>< /app-eventos>)
3. Utilize o JSON (eventos.json) para substituir o conte´udo da sua propriedade criada no item b) da quest˜ao 2 por este json com m´ultiplos
eventos.
4. Altere o HTML do seu componente eventos para exibir os m´ultiplos eventos utilizando o *ngFor
5. Alguns desses eventos s˜ao dispon´ıveis somente online e outros na modalidade online e presencial. Crie uma tag span com a mensagem ”Evento
Online” que ser´a exibida quando o evento for do tipo online. Al´em disso
esconda a localiza¸c˜ao completa de um evento caso ele seja somente online.
Utilize a diretiva ngIf para realizar essa tarefa.
