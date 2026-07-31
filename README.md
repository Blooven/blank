# Discord Message Scrambler

A Tampermonkey userscript that allows two users to exchange scrambled (encrypted) messages directly through Discord.

Instead of sending plain text, the script transforms your message into an unreadable format before it is sent. Anyone without the shared key will only see scrambled text. Users running the script with the same key automatically restore the original message when it is received.

---

## Features

* 🔐 End-to-end message scrambling between users with the same key
* 🔑 Shared secret key system
* ⚡ Automatic scrambling while typing
* 💬 Automatic restoration of incoming messages
* 🌐 Works directly inside Discord Web
* 🔓 Fully open source
* 🛠️ Runs locally through Tampermonkey

---

## How It Works

1. Two users agree on a shared secret key.
2. Both install this userscript.
3. Both configure the exact same key.
4. Messages sent between them are scrambled before being transmitted.
5. When the recipient receives the message, the script automatically restores the original text.

Users without the script (or with the wrong key) will only see unreadable scrambled text.

---

## Installation

1. Install **Tampermonkey**.
2. Install the latest release of this userscript.
3. Open Discord in your browser.
4. Configure your shared key.
5. Start chatting.

---

## Security

This project is intended to provide lightweight message privacy between consenting users.

The security depends entirely on:

* the strength of the shared key,
* the encryption implementation,
* and keeping the key private.

Never share your key publicly.

---

## Compatibility

* Discord Web
* Microsoft Edge
* Google Chrome
* Chromium-based browsers
* Tampermonkey

---

## Why?

Discord already encrypts traffic between your browser and Discord's servers (TLS), but Discord itself can still read message contents.

This project adds an extra layer of privacy by transforming messages before they are sent, allowing only users with the same shared key and this userscript to read them.

---

## Disclaimer

This software is provided **"AS IS"** under the MIT License.

The author provides no warranty of any kind and accepts no liability for damages, data loss, account actions, or misuse resulting from the use of this software.

Users are responsible for complying with Discord's Terms of Service and all applicable laws.

---

## Contributing

Pull requests, bug reports, feature suggestions, and security improvements are welcome.

If you discover a vulnerability, please open an issue or submit a pull request.

---

## License

Released under the **MIT License**.

See the `LICENSE` file for details.
