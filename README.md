# Entropi API Documentation

This directory contains the complete Mintlify documentation for Entropi API.

## Structure

```
docs/
├── mint.json                    # Mintlify configuration
├── introduction.mdx             # Project introduction
├── architecture.mdx            # System architecture
├── database.mdx                 # Database schema
├── services/
│   ├── overview.mdx            # Services overview
│   ├── image-service.mdx       # Image conversion service
│   ├── ocr-service.mdx         # OCR extraction service
│   ├── crop-service.mdx        # Smart cropping service
│   └── search-enrichment.mdx   # Search enrichment service
├── api-reference/
│   ├── analyze.mdx             # Main pipeline endpoint
│   └── authentication.mdx      # Auth endpoints
└── setup/
    ├── installation.mdx        # Installation guide
    └── configuration.mdx        # Configuration guide
```

## Deploying to Mintlify

1. **Install Mintlify CLI**:
   ```bash
   npm i -g mintlify
   ```

2. **Initialize Mintlify** (if not already done):
   ```bash
   mintlify init
   ```

3. **Preview locally**:
   ```bash
   mintlify dev
   ```

4. **Deploy**:
   ```bash
   mintlify deploy
   ```

## Customization

- **Logo**: Add logo files to `/logo/` directory (dark.svg, light.svg)
- **Favicon**: Add favicon.svg to root
- **Colors**: Edit `colors` in `mint.json`
- **Navigation**: Edit `navigation` array in `mint.json`

## Notes

- All MDX files use Mintlify components (Card, CardGroup, CodeGroup, etc.)
- Diagrams use Mermaid syntax
- Code examples include multiple languages where applicable

