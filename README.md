# Social Media Assets (Public)

Public, approved social media image assets for Buffer scheduling.

## Publish workflow
Use the helper script from CTO workspace:

```bash
/Users/georgeelias/.openclaw/agents/coding/workspace/scripts/publish_social_asset.sh \
  "/absolute/path/to/image.png" "optional-slug"
```

It will copy the file into this repo under `assets/YYYY/MM/`, commit, push, and print a public HTTPS URL.

## URL format
`https://georgeelias22.github.io/social-media-assets/assets/YYYY/MM/<slug>.<ext>`
