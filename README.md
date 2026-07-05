# Entropi API Documentation

This directory contains the complete Mintlify documentation for Entropi API.

## Structure

```
docs/
├── docs.json                    # Mintlify navigation & theme
├── introduction.mdx             # Project introduction
├── architecture.mdx             # Synchronous pipeline architecture
├── database.mdx                 # Database schema
├── getting-started/
│   ├── quickstart.mdx           # Five-minute end-to-end
│   └── core-concepts.mdx        # Mental models
├── guides/
│   ├── analyze-a-screenshot.mdx # Capture flow
│   ├── semantic-search.mdx      # Search flow
│   ├── handle-failures.mdx      # stumped + errors
│   └── run-tests.mdx            # pytest vs dev scripts
├── services/
│   ├── overview.mdx             # Services overview
│   ├── image-service.mdx        # Image conversion service
│   ├── vision-service.mdx       # Single-call visual understanding
│   ├── crop-service.mdx         # Local Pillow crop
│   └── embedding-service.mdx    # Multimodal search indexing
├── api-reference/
│   ├── authentication.mdx       # Auth endpoints
│   ├── analyze.mdx              # Synchronous capture endpoint
│   ├── products.mdx             # Get product + field reference
│   └── search.mdx              # Semantic search endpoint
├── configuration/
│   └── environment-variables.mdx
└── self-hosting/
    ├── requirements.mdx
    ├── installation.mdx
    └── upgrades.mdx
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

