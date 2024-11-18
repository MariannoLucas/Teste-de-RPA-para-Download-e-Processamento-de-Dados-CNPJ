# Teste-de-RPA-para-Download-e-Processamento-de-Dados-CNPJ
Automatizar o download e processamento mensal dos dados do CNPJ usando  UiPath.

Eu havia comentado com Kaleo que eu trabalho a quase 10 anos com RPA mas não sou desenvolvedor, atuo na identificação de oportunidades, criação de documentação, Líder de projeto, Líder técnico, e o ponto focal entre desenvolvimento e áreas de negócio. Esse foi meu primeiro desenvolvimento, já que nunca precisei atuar nessa frente.  Gastei 10 horas para o desenvolvimento, e para um trabalho bacana eu estimaria 40h. Para realizar o teste de funcionamento será necessário alterar, pasta de salvamento e destino do e-mail.

Itens do escopo não contemplados
- Reduzi a quantidade de arquivos no caminho Dados Abertos CNPJ para um 1 reduzir o tempo de desenvolvimento e teste e conseguir mostrar mais coisas.
- Ainda seria necessário acessar o orquestrador e configurar a execução de 2 em 2 horas. 
- O código está com valores fixos para as datas de atualização e extração,  guardei o texto com a informação de data que se encontra no site e precisava retirar o final dele que é onde a data estava escrita.

Oportunidades
- Variáveis para caminhos
- Variáveis para e-mail 
- Estruturação de pastas para não perder o histórico
- Código preventivo de bugs (Delay, loops de tentativas, etc)
- Revisão de código (boas práticas)
- Melhorar textos e layouts de envio de e-mails

Riscos
- O botão salvar na página do dicionário está funcionando algumas vezes outras não, será necessário mais testes para verificar uma melhor forma de desenvolver.
- Por ser um site externo é possível a quebra do robô sem aviso.
