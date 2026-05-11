# Imagem em imagem (vídeo)

O weballoon inclui um **painel de vídeo flutuante** (em inglês pode aparecer como **PiP Video**) para ver um stream enquanto usa outras partes da app.

## Abrir o painel

Prima **Shift+S** (ou o mesmo atalho a partir de dentro de uma app incorporada).

## Utilização

1. Abre-se uma pequena janela flutuante.
2. Cole ou escreva um **URL de página de vídeo** e prima **Reproduzir** (ou envie o formulário).
3. Em anfitriões comuns, o weballoon converte ligações para um leitor **incorporado** quando possível:
   - **YouTube** (`youtube.com/watch?v=…` ou `youtu.be/…`)
   - **Vimeo**
   - **Dailymotion**
4. Outros URLs carregam **diretamente no iframe**; se reproduzem depende das regras de incorporação do site (alguns bloqueiam iframes).

## Controlos

- **Fechar** — fecha o flutuante e limpa o URL.
- **Alterar URL** (com vídeo ativo) — volta ao passo de introdução do URL.
- **Repor posição** — se moveu a janela, um controlo pode repor o layout (ícone com setas tipo expandir na barra de controlos).
- Pode **arrastar** o painel pelo cromo vazio (não por campos, botões nem iframe).

## Notas

- **Não** é a API nativa de imagem em imagem do navegador para separadores arbitrários; é o **flutuante PiP** dedicado do weballoon com reprodução em iframe.
- A reprodução automática pode depender do site e das definições de áudio do sistema.
