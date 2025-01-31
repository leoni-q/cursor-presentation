# The Autonomous Coding Revolution

A presentation about the evolution of AI in software engineering, focusing on Cursor's capabilities and the future of coding.

## Getting Started

To run this presentation locally:

```bash
# Install dependencies
npm install

# Start the presentation
npm run dev
```

The presentation will open in your default browser at `http://localhost:3030`.

## Features

- Interactive slides with transitions
- Code highlighting
- Embedded Tweet
- Responsive layouts
- Click animations

## Modifying the Presentation

The main presentation content is in `slides.md`. Each slide is separated by `---`.

### Slide Layouts

The presentation uses various layouts:
- `default` - Standard slide
- `two-cols` - Two-column layout
- `image-right` - Image on the right side
- `center` - Centered content
- `end` - End slide

### Styling

Custom styles are defined at the bottom of `slides.md`. You can modify the gradient colors and other styles there.

## Building for Production

To build the presentation for production:

```bash
npm run build
```

To export as PDF:

```bash
npm run export
```

## License

MIT 