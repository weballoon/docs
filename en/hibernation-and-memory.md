# App hibernation & memory

weballoon limits how many embedded app sessions stay **fully active** at once so your computer stays responsive.

## How it behaves (plain language)

- When you have **an app open** in front of you, weballoon keeps a small number of other sessions “live” for quick switching; additional ones may be **hibernated**.
- When you are back on **My Apps** (no app filling the screen), even fewer non-essential sessions stay live in the background.
- **Hibernated** here means the session is parked: weballoon saves where you were and can **mute audio** for that session until you open it again. Opening the app again brings it back (you may see a brief reload).

Apps with **Run in background** enabled in **Settings → Notifications** are treated specially: they stay mounted so notification-related behavior can keep working. They still count toward memory use—see the note in Settings (about **50–150 MB** per background app).

## What you should do

- If the machine feels heavy, reduce the number of **Run in background** apps.
- Close app views you do not need (title bar **Close app**).
- Use **Task Manager** in Settings to see which apps use the most CPU or RAM.

## Related

- [Task Manager](task-manager.md)  
- [Notifications](notifications.md)  
