# Annis Tabellenhelfer

A small table maker for people who don't know (or don't care) whether they need Word or Excel.

I built it for my mother-in-law. She needed tables now and then and got stuck every time on which program to open. Here she picks Word or Excel (with a short hint on which fits), sets columns and rows, types her content, checks the preview, and downloads the file. A few clicks, nothing to install.

## How to use it

1. Download `Annis_Tabellenhelfer.html`.
2. Open it in any browser, on a phone or a computer.
3. That's it. It works fully offline: no account, no server, no AI, nothing leaves your device.

The interface is in German. The greeting, the name in the footer and the horses and flowers are made for Anni. Change them to whoever you're building it for.

## How it's built

- One HTML file with plain HTML, CSS and JavaScript.
- Word (.docx) and Excel (.xlsx) files are generated in the browser with [JSZip](https://stuk.github.io/jszip/) (bundled inside the file, MIT license).
- Design rule: nothing gets added unless it removes friction.

## License

MIT, see [LICENSE](LICENSE). Take it, change it, give it to your own Anni.

Built by [Noni Siampakouli](https://nonisiampakouli.de), with Claude as my development team.
