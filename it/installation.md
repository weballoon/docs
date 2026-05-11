# Installazione e piattaforme supportate

I build desktop ufficiali coprono **macOS**, **Windows** e **Linux**, su **Intel 64 bit (x64)** e **Apple Silicon / ARM64** dove applicabile.

## macOS

Gli installer sono **DMG** e **ZIP** (entrambe le architetture nei build di release). Dopo aver aperto il DMG, trascina **weballoon** in Applicazioni (o il tuo flusso abituale).

**Deep link:** l’app registra lo schema `weballoon://` così i **magic link** e-mail riportano all’app al clic.

## Windows

Il formato di release è **NSIS** (installer) per x64 e arm64.

Lo stesso schema **`weballoon://`** vale per completare il magic link.

## Linux

I release usano **AppImage** (x64 e arm64). Gli aggiornamenti automatici in-app su Linux possono funzionare solo se hai installato da un pacchetto di release supportato (l’app spiega se gli aggiornamenti non sono disponibili).

## Aggiornamenti

In **Impostazioni**, nell’area account, la scheda **Aggiornamenti app** consente di **controllare aggiornamenti** e, quando un download è pronto, di **riavviare per aggiornare**. Se un aggiornamento è stato scaricato in background, weballoon può chiederti di riavviare quando ti conviene.

Alcuni ambienti (es. build di sviluppo locale) non offrono aggiornamenti automatici; la scheda indica che non sono disponibili e il motivo.

## Requisiti di sistema

weballoon è un runtime web desktop. Per un uso fluido basta un computer moderno con alcuni GB di RAM libera; ogni app aperta o in background usa memoria aggiuntiva (vedi [Ibernazione e memoria](hibernation-and-memory.md)).
