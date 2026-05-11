# Resolução de problemas

Passos calmos e práticos. Se nada ajudar, anote a **versão do weballoon** (Definições → Atualizações da app) e o **SO** ao pedir suporte.

## O magic link não associa o dispositivo

- Confirme que clicou na ligação na **mesma máquina** onde o weballoon está instalado.
- macOS / Windows: assegure que ligações **`weballoon://`** abrem no weballoon (definições do sistema do «manipulador predefinido»).
- Experimente **Reenviar ligação** em **Definições → Conta** após o período de espera.
- Verifique pastas de spam.

## «Limite do plano gratuito atingido»

Tem **10 apps** ou está a tentar criar mais de **2** espaços no Free. Remova uma app ou espaço, ou subscreva em **Planos** ([Planos e faturação](plans-and-billing.md)).

## O site parece partido ou em branco

- **Recarregar** na barra de título.
- **Definições → Bloqueador de anúncios** — experimente desligar o bloqueio **só para essa app**.
- **Definições → Proxy** — confirme anfitrião, porta e exclusões; guarde e deixe a app recarregar.

## Sem notificações de um site

- Ative **Correr em segundo plano** para essa app em **Definições → Notificações**.
- O site deve usar mesmo **notificações web**; alguns só usam avisos na página.
- Se **estiver dentro** dessa app com foco, o weballoon pode omitir duplicar entradas na campainha interna (as notificações do SO podem ainda aparecer consoante o site).

## O atalho não funciona

- Clique fora dos campos do site (barra de título ou cromo do weballoon) e tente de novo ([Atalhos de teclado](keyboard-shortcuts.md)).
- Os saltos **Ctrl/Cmd+número** para o espaço só registam **dentro** de uma app web aberta; em **As minhas apps** ou **Definições** use o botão de espaço ou **Shift+W**.

## CPU ou RAM altos

- **Definições → Gestor de tarefas** — ordene por memória ou CPU.
- Reduza apps com **Correr em segundo plano**.
- Feche vistas de app que não use.

## As atualizações nunca aparecem

O cartão **Atualizações da app** explica quando as verificações automáticas estão **desativadas** (builds de desenvolvimento, algumas configurações Linux ou variáveis de ambiente). Instale um **release** oficial quando possível.

## Fechei a janela mas o weballoon «ainda está aí» (Windows / Linux)

Pode haver um **ícone na bandeja**. **Clique direito → Sair** para sair por completo, ou clique no ícone para mostrar a janela de novo ([Resumo das definições](settings.md)).

## Tema errado após mudança do sistema

O tema do weballoon é **manual** (escuro / claro) em Definições, não «seguir o sistema» no seletor atual — escolha o tema que quiser em **Aspeto**.
