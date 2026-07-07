[← Back to Root](https://github.com/httperry/snoopy)

# Resources

This directory contains static assets used by the project and its documentation

## Structure

```
Resources/
└── Icons/
    └── Snoopy Exports/
        ├── Snoopy-macOS-Default-1024@1x.png    # Default icon (light mode)
        ├── Snoopy-macOS-Dark-1024@1x.png        # Dark background variant
        ├── Snoopy-macOS-ClearDark-1024@1x.png   # Clear dark variant
        ├── Snoopy-macOS-ClearLight-1024@1x.png  # Clear light variant
        ├── Snoopy-macOS-TintedDark-1024@1x.png  # Tinted dark variant
        └── Snoopy-macOS-TintedLight-1024@1x.png # Tinted light variant
```

## Icons

The project icon is exported in multiple variants for use across different backgrounds and contexts. GitHub READMEs use the `<picture>` element to serve the correct variant based on the viewer's system theme — Default for dark mode, Dark for light mode
