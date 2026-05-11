# Instalação e plataformas suportadas

Os builds oficiais de ambiente de trabalho visam **macOS**, **Windows** e **Linux**, em **Intel 64 bits (x64)** e **Apple Silicon / ARM64** quando aplicável.

## macOS

Os instaladores são **DMG** e **ZIP** (ambas as arquiteturas nos builds de release). Depois de abrir o DMG, arraste o **weballoon** para Aplicações (ou o seu fluxo habitual).

**Deep link:** a app regista o esquema `weballoon://` para que os **magic links** por email voltem à app ao clicar.

## Windows

O formato de release é **NSIS** (instalador) para x64 e arm64.

O mesmo esquema **`weballoon://`** aplica-se à conclusão do magic link.

## Linux

Os releases usam **AppImage** (x64 e arm64). As atualizações automáticas na app em Linux podem funcionar apenas quando instalou a partir de um pacote de release suportado (a app explica se as atualizações estiverem indisponíveis no seu ambiente).

## Atualizações

Em **Definições**, na área da conta, o cartão **Atualizações da app** permite **procurar atualizações** e, quando uma transferência estiver pronta, **reiniciar para atualizar**. Se uma atualização for transferida em segundo plano, o weballoon pode pedir-lhe que reinicie quando for conveniente.

Alguns ambientes (por exemplo builds de desenvolvimento local) não oferecem atualizações automáticas; o cartão indica que estão indisponíveis e o motivo.

## Requisitos de sistema

O weballoon é um runtime web de ambiente de trabalho. Para um uso fluido basta um computador moderno normal com alguns GB de RAM livre; cada app aberta ou em segundo plano usa memória adicional (ver [Hibernação e memória](hibernation-and-memory.md)).
