# Growth Android app

Aplicação Android com WebView local para o calendário Growth e notificações nativas diárias às 08:00 e 20:00.

## Compilar

O workflow GitHub Actions compila um APK debug em cada push para `main`, ou manualmente em Actions > Build Growth APK > Run workflow. O ficheiro fica disponível em Artifacts como `Growth-APK`.

As notificações precisam de ser autorizadas na primeira abertura. A exactidão do horário pode variar ligeiramente devido às políticas de bateria do Android. Se necessário, permitir notificações e funcionamento em segundo plano nas definições do telefone.
