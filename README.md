# Comandos uteis do dia a dia
 
## Iniciar o container automaticamente com o sistema
  <p> no	Não reinicia o contêiner automaticamente. (o padrão)</p>
  <p> on-failure	Reinicie o contêiner se ele sair devido a um erro, que se manifesta como um código de saída diferente de zero.</p>
  <p> unless-stopped	Reinicie o contêiner, a menos que seja explicitamente interrompido ou o próprio Docker esteja parado ou reiniciado.</p>
  <p> always	Sempre reinicie o contêiner se ele parar.</p>
  
  docker update –restart=always <container>
