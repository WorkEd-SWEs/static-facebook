# Facebook Clone - Static Export

This is a standalone static export of the Facebook Clone app.

## Quick Start

```bash
# Using Python (simplest)
python3 -m http.server 3000

# Or using Node.js
npx serve -l 3000
```

Then open:
http://localhost:3000/section/

## Directory Structure
- `/section/` - The main app (Facebook clone)
- `/section/profile/100` - Example profile page
- `/section/_next/` - Static assets (JS, CSS)
- Images and other assets

## Integration
To include this in another static site:
1. Copy everything into your projects public/section/ directory
2. The app will be available at /section/

## Notes
- This is a complete static export - no build tools or Node.js required
- All assets are included (images, JS, CSS)
- Requires a static file server that preserves paths (most do)

