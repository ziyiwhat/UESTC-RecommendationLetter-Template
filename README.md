# UESTC Recommendation Letter Template

A professional LaTeX template for creating recommendation letters with the University of Electronic Science and Technology of China (UESTC) letterhead and branding.

## 📋 Overview

This template provides a standardized format for UESTC faculty members to write recommendation letters. It includes:

- **Official UESTC letterhead** with university logo
- **Professional formatting** following academic standards
- **Customizable contact information** for faculty members
- **Watermark background** with UESTC branding
- **Signature support** with digital signature capability
- **Page numbering** and proper document structure

## 🎯 Features

- **UESTC Branding**: Includes official university logo and color scheme
- **Professional Layout**: Clean, academic-style formatting
- **Customizable**: Easy to modify personal information and content
- **Signature Support**: Can include digital signatures
- **Watermark**: Subtle UESTC background watermark
- **Multi-language**: Supports both English and Chinese content
- **Print-ready**: Optimized for both digital and print output

## 📁 Project Structure

```
UESTC-RecommendationLetter-Template/
├── main.tex              # Main LaTeX document
├── uestcLetter.cls       # Custom document class
├── content.tex           # Letter content (customizable)
├── figures/              # Graphics and images
│   ├── UESTC.pdf        # UESTC logo
│   ├── UESTC_bg.pdf     # Background watermark
│   └── signature.pdf     # Digital signature
├── main.pdf              # Generated output
└── README.md            # This file
```

## 🚀 Quick Start

### Prerequisites

- LaTeX distribution (TeX Live, MiKTeX, or similar)
- Required LaTeX packages (automatically included):
  - `tikz`
  - `xcolor`
  - `babel`
  - `fancyhdr`
  - `graphicx`
  - `eso-pic`
  - `hyperref`

### Usage

1. **Clone or download** this repository
2. **Customize** the personal information in `main.tex`:
   - Update professor name, department, and contact details
   - Modify the address information
   - Add your digital signature to `figures/signature.pdf`
3. **Edit** the letter content in `content.tex`
4. **Compile** the document:
   ```bash
   pdflatex main.tex
   ```

## ⚙️ Customization

### Personal Information

Edit the following sections in `main.tex`:

```latex
\def\name{Prof. PNAME \\
COLLEGE NAME  \\
University of Electronic Science and Technology of China \\
Email: EMAIL \\
Homepage: HOMEPAGE
}

\def\Where{%
    School of Information and Communication Engineering,
}

\def\Address{%
    No.2006, Xiyuan Ave,\\
    West Hi-Tech Zone,
}

\def\CityZip{Chengdu, Sichuan, 611731}
```

### Letter Content

Replace the content in `content.tex` with your recommendation letter text:

```latex
% Replace \lipsum[1-6] with your actual letter content
Dear Admissions Committee,

[Your recommendation letter content here...]

Sincerely,
```

### Signature

- Place your digital signature as `figures/signature.pdf`
- The template will automatically include it if the file exists
- If no signature file is found, it will use a text-based signature

## 🎨 Features in Detail

### Letterhead
- Official UESTC logo in the header
- Professional university branding
- Clean, academic layout

### Watermark
- Subtle UESTC background watermark
- Can be enabled/disabled as needed
- Maintains readability while adding branding

### Page Formatting
- Standard letter paper size
- Proper margins and spacing
- Page numbering (Page X of Y)
- Footer with university information

### Contact Information
- Faculty member details
- Department and school information
- University address and contact details

## 📝 Example Output

The template generates a professional recommendation letter with:
- UESTC letterhead at the top
- Faculty contact information
- Recipient address section
- Main letter content area
- Signature section with digital signature support
- University footer information

## 🤝 Contributing

This template was originally created by Brian Wood and has been modified by:
- Shaozuo Yu (AugustYum@outlook.com) - Tongji University modifications
- Rizhong Lin (rizhonglin@tongji.edu.cn) - Maintenance and updates
- Ziyi Wang (ziyiwhat@gmail.com) - UESTC adaptations

Contributions are welcome! Please feel free to:
- Report issues or bugs
- Suggest improvements
- Submit pull requests for enhancements

## 📄 License

This template is provided as-is for academic use. Please respect the original authors' work and the university's branding guidelines.

## 📞 Support

For questions or issues:
- Check the LaTeX compilation logs for errors
- Ensure all required files are present in the `figures/` directory
- Verify that your LaTeX distribution includes all required packages

---

**Note**: This template is specifically designed for UESTC faculty members writing recommendation letters. Please ensure compliance with your institution's letterhead and branding policies.