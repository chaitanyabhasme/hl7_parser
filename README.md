# HL7 v2.x Message Parser

A simple, modern HL7 version 2.x message parser and visualizer for the web.  
Parse, explore, and understand HL7 messages with full segment/field linking and field descriptions—all in your browser, no backend required.

**Live demo:**  
[HL7 Parser](https://chaitanyabhasme.github.io/hl7_parser/index.html)

## How to Use

- Paste or type your HL7 v2.x message into the input box.
- Click _Parse Message_ to visualize, expand, and explore fields and their meanings.
- No installation or server is needed—just open `index.html` in any web browser.

## Features

- **Zero dependencies** (except CDN for React, Babel, Tailwind, Lucide icons—works offline after first load).
- Parses most mainstream HL7 v2.x messages (ADT, ORU, ORM, etc).
- Field and segment descriptions included.
- Intuitive, mobile-friendly UI (Tailwind CSS).
- Copy individual segments.
- Expand/collapse all segments.
- Examples provided for easy testing.

## File Reference

- `index.html` &mdash; Main app (browser only)
- `fields_and_descriptions.js` &mdash; HL7 field/segment descriptions (loaded externally for maintainability)

## License

MIT License.  
See `LICENSE` file for details.

## Acknowledgments

- [React](https://react.dev/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Lucide Icons](https://lucide.dev/)
- HL7 message standards ([www.hl7.org](https://hl7.org/))
