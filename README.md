# Comandos úteis do dia a dia
 
## Iniciar o container automaticamente com o sistema
### Utilize ao criar o container o parametro ‘ – – restart = {valor} ‘ veja seus valores:
  <p> <b>no</b>	Não reinicia o contêiner automaticamente. (o padrão)</p>
  <p> <b>on-failure</b>	Reinicie o contêiner se ele sair devido a um erro, que se manifesta como um código de saída diferente de zero.</p>
  <p> <b>unless-stopped</b>	Reinicie o contêiner, a menos que seja explicitamente interrompido ou o próprio Docker esteja parado ou reiniciado.</p>
  <p> <b>always	Sempre</b> reinicie o contêiner se ele parar.</p>
  
### Caso o container já esteja rodando, utilize da seguinte forma:   
  docker update –restart=always container
