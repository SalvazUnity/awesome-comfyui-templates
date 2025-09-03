# Contributing

Want to share your ComfyUI templates? Great! Here's how:

## Quick Start
1. Fork this repo
2. Add your template in the right category
3. Follow the template structure below
4. Submit a pull request

## Template Structure
```
templates/[category]/[template-name]/
├── workflow.json    # ComfyUI workflow (REQUIRED)
├── README.md       # Description & instructions (REQUIRED)  
├── preview.png     # Preview image (REQUIRED)
└── examples/       # Example outputs (optional)
```

## Template README Format
```markdown
# Template Name

Brief description of what it does.

![Preview](preview.png)

## Requirements
- ComfyUI version X.X+
- Models: [list with download links]
- Custom nodes: [list if needed]

## Usage
1. Import workflow.json into ComfyUI
2. Download required models
3. Queue the prompt

## Credits
Author: Your Name
```

## Categories
- `image-generation/` - Text/image-to-image workflows
- `video-generation/` - Text/image-to-video workflows  
- `audio-processing/` - Audio generation
- `image-processing/` - Enhancement, upscaling, etc.
- `experimental/` - Cutting-edge workflows

## Guidelines
- Test your template before submitting
- Use clear file names and descriptions
- Include model download links
- Keep preview images under 2MB

Thanks for contributing! 🎉
