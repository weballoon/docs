# Privacidade e dados locais

Abra **Definições → Privacidade e dados**.

## O que permanece local

A app enfatiza que os seus **dados ficam no seu computador**. O ecrã de definições mostra:

- **Armazenamento** aproximado usado na área de dados do utilizador.
- Contagens de **apps** e **espaços de trabalho**.
- Caminho para o ficheiro principal da base de dados local (mostrado como `weballoon.json` na pasta de dados do utilizador).
- **Abrir pasta** — abre esse diretório de dados no gestor de ficheiros do sistema.

## Limpar dados

- **Limpar dados** (por app) — Remove cookies, cache e dados do site armazenados dessa sessão isolada. A app pode recarregar da próxima vez que abrir.
- **Limpar todos os dados** — Remove cookies, cache e armazenamento **de todas as apps**. É destrutivo; o weballoon pede confirmação.

## Limpeza automática (ao sair)

Duas opções persistem entre reinícios:

1. **Limpar automaticamente ao sair** — Ao sair do weballoon, os dados de navegação das apps são limpos (cookies, cache e os tipos de armazenamento que a app limpa ao sair).
2. **Limpar cache automaticamente** — Apesar de texto antigo falar em «periodicamente», a implementação limpa a **cache ao sair do weballoon** (não com um temporizador durante o dia). Se ambas as opções automáticas estiverem ativas, prevalece o caminho mais forte de «limpar dados de navegação ao sair».

Use estas opções se quiser começar limpo após cada sessão.

## Do Not Track

**Enviar cabeçalho Do-Not-Track** pede aos sites que respeitem o DNT. Nem todos o fazem; é um pedido, não uma garantia.

## Relatórios de falhas e erros

**Partilhar relatórios de falhas e erros** está **desligado por predefinição**. Se ativar, a app descreve o envio de **diagnósticos técnicos sanitizados** para melhorar a estabilidade, **não** o seu conteúdo de navegação, credenciais nem histórico.

## Isolamento de apps (lembrete)

Cada app tem **armazenamento isolado**. Limpar ou a limpeza automática afeta **essa partição**, não as suas outras apps.

Ver [Sessões isoladas](isolated-sessions.md).
