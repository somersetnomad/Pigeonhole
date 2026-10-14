# Pigeonhole

Disposable email inboxes that live in your browser. No sign-up, no login.

Pigeonhole is a single web page (`index.html`). Open it and you get a working email address straight away. Your inboxes are saved in the browser, so they're still there next time you open the page.

## Features

- **Instant address** on first visit, or choose your own name and domain
- **Several inboxes side by side**, each with an unread count
- **Verification codes detected automatically** with one-tap copy, plus quick buttons for "verify" and "confirm" links
- **Live inbox** that checks for new mail every 5 seconds
- **Desktop alerts and a sound** when mail arrives (optional)
- **Tracking protection**: remote images are blocked until you choose to show them
- **Safe viewing**: emails render in a sandboxed frame that can't run scripts
- **Backup code** to move your inboxes to another browser or restore them after clearing data
- Search, attachments, delete messages or whole inboxes, dark mode, phone layout

## Using it

- **Locally:** download `index.html` and double-click it.
- **As a website:** turn on GitHub Pages for this repository (Settings → Pages → deploy from the `main` branch, root folder). The site will be at `https://somersetnomad.github.io/pigeonhole/`.

## Limits

- Receive-only. It can't send email.
- Addresses use the domains provided by [Mail.tm](https://mail.tm), which delivers the mail. Their terms require a visible link back to Mail.tm (included in the page footer) and don't allow reselling the service.
- Inboxes are stored only in your browser. Clearing site data removes them unless you've kept a backup code.
- Messages are deleted by the provider after a while. Don't use this for anything important.

## Licence

MIT. See [LICENSE](LICENSE).
