Neste curso, as classes modificadas foram:

Pasta: configuration - AsyncConfiguration = Serviu para configurar a criacao de threads do spring<br>
Pasta: email - EmailRelatorioGerado = Padronizacao e utilizador do sender de email<br>
Pasta: service - AgendamentoService = Serviu para configurar o cron de envio de "email" de relatorios (O Cron cria uma thread paralela ao restante do codigo)<br>
Pasta: service - RelatorioService = Configuracao da sincronizacao das threads de relatorios do contexto do projeto, utilizacao de novo conceito chamado CompletableFuture<br>
                 Serve para recuperar um valor dentro de uma funcao que nao pode ter retorno, mas ainda devemos recuperar algum valor de dentro da funcao<br>
Pasta: raiz do projeto - AdopetStoreApplication - Inserindo anotacoes responsaveis habilitar as threads e agendamento no spring<br>
