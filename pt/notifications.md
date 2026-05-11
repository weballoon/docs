# Notificações

O weballoon trata duas ideias relacionadas: **notificações ao nível do SO** de sites que usam a API de notificações do navegador, e uma **lista de notificações na app** para se atualizar sem procurar toasts.

## Centro de notificações na app

- Clique na **campainha** na doca, ou **Shift+N** (quando o foco o permitir; ver [Atalhos de teclado](keyboard-shortcuts.md)).
- Pode **marcar tudo como lido**, abrir um item para ir à app ou dispensar entradas.
- Enquanto **já está a ver** uma app, notificações novas dessa mesma app **não são duplicadas** na lista interna (a app pode ainda usar a notificação do SO se o site o suportar).

As notificações ficam numa lista curta (até 100 itens recentes) para o painel continuar útil.

## «Correr em segundo plano» (por app)

Em **Definições → Notificações**, cada app tem uma opção com o rótulo **Run in background** na interface em inglês. Quando ativa:

- A sessão dessa app pode manter-se ativa para que coisas como **websockets** continuem a funcionar enquanto olha para outra app ou outro espaço.
- O weballoon mostra um lembrete de que **cada** app em segundo plano usa cerca de **50–150 MB** de memória (aproximado; o uso real varia por site).

Se ainda não tiver apps, o painel explica que deve adicionar apps primeiro e depois escolher quais devem continuar a correr.

## Uso prático

- Ative **Correr em segundo plano** em chat ou email onde quer alertas enquanto usa outras partes do weballoon.
- Deixe desativado em sites pesados ou pouco usados para poupar RAM.

Ver também [Hibernação e memória](hibernation-and-memory.md).
