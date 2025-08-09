# Contributing to Azure AI Content Understanding Assets

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit [Contributor License Agreements](https://cla.opensource.microsoft.com).

# Contributing Guidelines

## 🎯 Adding New Assets

### 1. **File Organization**

```
├───.github
├───documents
├───images
└───videos
    └───enterprise     # Enterprise Video Content
    └───learning       # e-Learning content from the web
    └───marketing      # Advertisements and promo finding
    └───entertainment  # TV and Movie samples
    
```

### 2. **File Naming Convention**
- Use lowercase with hyphens: `product-name.mp4`
- Be descriptive: `some-smartwatch-ad.mp4`
- Avoid spaces and special characters

### 3. **File Requirements**
- **Repository Max capacity**: 1GB
- **Video format**: MP4 (H.264 codec preferred)
- **Max file size**: 50MB per file
- **Resolution**: 1280x720 minimum
- **Audio**: Include if relevant

### 4. **Pull Request Process**

All assets must be approved by the owners of this repository. Make sure you go thorugh legal review of your files before submitting a PR request.

#### **For New Assets:**
1. **Create branch**: `git checkout -b add-{product-name}-video`
2. **Add files**: Place in appropriate category folder
3. **Update catalog**: Update `README.md` table
4. **Test URLs**: Verify raw URLs work
5. **Create PR**: Use descriptive title and fill template