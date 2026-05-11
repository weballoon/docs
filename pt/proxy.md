# Configuração de proxy

Abra **Definições → Proxy**.

## Encaminhamento por aplicação

Cada app pode ser encaminhada pelo seu **próprio** proxy ou **nenhum**. Útil para:

- Proxies HTTP corporativos só em apps de trabalho.
- Acesso SOCKS para ferramentas específicas.
- Testes regionais combinados com sessões isoladas.

## Campos (com proxy ativo)

- **Protocolo** — HTTP, HTTPS, SOCKS4 ou SOCKS5.
- **Anfitrião** e **Porta**.
- **Nome de utilizador** (opcional).
- **Palavra-passe** (opcional). A interface explica que uma palavra-passe guardada pode ficar em branco para manter a anterior, e há uma ação para **limpar palavra-passe guardada**.
- **Regras de exclusão** — Lista estilo vírgulas (exemplo na app: `localhost, 127.0.0.1, *.internal`).

## Guardar

**Guardar e recarregar** guarda as definições e **recarrega essa aplicação** para que ligações novas usem a rota. A app avisa que alterações de proxy **fecham ligações existentes** da app afetada.

## Nota de segurança

A área **Conta** indica que as **palavras-passe do proxy** são encriptadas neste dispositivo e **não** são sincronizadas com a nuvem.

## Se a lista estiver vazia

Adicione pelo menos uma aplicação primeiro; o ecrã do proxy explica isso.
