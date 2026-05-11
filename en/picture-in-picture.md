# Picture in picture (video)

weballoon includes a **floating video panel** (labeled **PiP Video** in English) for watching a stream while using other parts of the app.

## Opening the panel

Press **Shift+S** (or use the shortcut bridge from inside an embedded app—same key).

## Using it

1. A small floating window opens.
2. Paste or type a **video page URL** and press **Play** (or submit the form).
3. For common hosts, weballoon converts links to an **embed** player when possible:
   - **YouTube** (`youtube.com/watch?v=…` or `youtu.be/…`)
   - **Vimeo**
   - **Dailymotion**
4. Other URLs load **directly in the iframe**; whether they play depends on the site’s embed rules (some sites block iframes).

## Controls

- **Close** — closes the floater and clears the URL.
- **Change URL** (when a video is active) — returns to the URL entry step.
- **Reset position** — if you moved the window, a control can snap layout back (icon with expand-style arrows in the control bar).
- You can **drag** the panel by empty chrome (not by inputs, buttons, or the iframe).

## Notes

- This is **not** the browser’s native Picture-in-Picture API for arbitrary tabs; it is weballoon’s dedicated **PiP floater** with iframe playback.
- Autoplay may depend on the site and your system audio settings.
