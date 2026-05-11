# Hibernação e memória da app

O weballoon limita quantas sessões incorporadas permanecem **totalmente ativas** de uma vez para o computador continuar responsivo.

## Como se comporta (linguagem simples)

- Com **uma app aberta** à frente, o weballoon mantém um pequeno número de outras sessões «vivas» para mudança rápida; as adicionais podem **hibernar**.
- De volta a **As minhas apps** (nenhuma app em ecrã inteiro), ainda menos sessões não essenciais ficam vivas em segundo plano.
- **Hibernar** aqui significa estacionar a sessão: o weballoon guarda onde estava e pode **silenciar o áudio** dessa sessão até voltar a abrir. Ao reabrir pode haver um recarregamento breve.

Apps com **Correr em segundo plano** ativado em **Definições → Notificações** são tratadas de forma especial: permanecem montadas para o comportamento relacionado com notificações. Continuam a contar para a memória — ver a nota em Definições (cerca de **50–150 MB** por app em segundo plano).

## O que pode fazer

- Se o computador estiver pesado, reduza o número de apps com **Correr em segundo plano**.
- Feche vistas de app que não precise (**Fechar app** na barra de título).
- Use o **Gestor de tarefas** em Definições para ver que apps usam mais CPU ou RAM.

## Relacionado

- [Gestor de tarefas](task-manager.md)  
- [Notificações](notifications.md)  
