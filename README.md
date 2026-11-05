# ReadEase

**A calmer way to read.**

ReadEase is a small, browser-based reading helper. Paste or type text, make it easier to see, and listen to it read aloud. It is designed as a lightweight, beginner-friendly open-source project.

## Features

- Live text preview and word count
- Adjustable text size
- Optional wider line and letter spacing
- High-contrast colour mode
- Read aloud, pause, resume, and stop controls using your browser's speech feature
- Responsive layout for desktop and mobile
- No account, installation, external library, or server required
- Text stays in the browser; the project does not upload or save it

## Run it

1. Download or clone this repository.
2. Open `index.html` in a modern web browser.
3. Paste some text or choose **Try sample text**.

For local development, you can also run a simple static server from this folder:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Publish with GitHub Pages

1. Create a public GitHub repository named `readease`.
2. Add `index.html`, `README.md`, and `LICENSE`.
3. Open the repository's **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`, then save.
6. Wait for GitHub Pages to publish the site. The URL will appear in the Pages settings.

## Privacy

ReadEase runs entirely in the browser. It does not send text to a server, use analytics, or store pasted content. The read-aloud feature uses the browser's built-in speech synthesis support. Speech availability and voice quality depend on the user's browser and device.

## Accessibility notes

The interface includes semantic HTML, labels, keyboard-visible focus styles, status announcements, responsive text controls, and a high-contrast option. This is a starter project, not a claim of full WCAG conformance. Contributions that improve accessibility are welcome.

## Contributing

Issues and pull requests are welcome. Please describe the problem, the change, and how you tested it. Keep the project dependency-free where practical and avoid adding analytics or transmitting users' text.

## Roadmap ideas

- Add language and voice selection when supported by the browser
- Add a dyslexia-friendly display option using a locally available font
- Add automated accessibility checks
- Add translations for the interface

## License

This project is released under the MIT License. See [LICENSE](LICENSE).
