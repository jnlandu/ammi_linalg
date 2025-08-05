# AMMI Linear Algebra Presentation

A comprehensive LaTeX Beamer presentation on Linear Algebra fundamentals designed for Master's students in Artificial Intelligence and Machine Learning at the African Masters of Machine Intelligence (AMMI).

## Overview

This presentation covers essential linear algebra concepts with a focus on applications in AI/ML, including:

- **Motivation**: Why linear algebra is crucial for AI/ML
- **Vectors**: Operations, inner products, norms, and geometric interpretations
- **Matrices**: Definitions, operations, and special matrix types
- **Linear Transformations**: Matrix representations and geometric understanding
- **Advanced Topics**: Orthogonality, Gram-Schmidt algorithm, and inequalities

## Repository Structure

```
ammi-linalg/
├── main.tex                          # Main presentation file
├── main_redesigned_clean.tex          # Modern redesigned version
├── preamble.tex                       # Original preamble
├── preamble_modern.tex                # Modern styling preamble
├── motivation.tex                     # Motivation section
├── vectors_innerp_norms.tex           # Comprehensive vector theory
├── matrices_definitions.tex           # Matrix fundamentals
├── linear_transformations_definitions.tex  # Linear transformations
└── README.md                          # This file
```

## Features

### Modern Design
- **Theme**: Madrid with whale color scheme
- **Aspect Ratio**: 16:9 for modern displays
- **Typography**: Enhanced fonts and mathematical notation
- **Colors**: Custom color palette optimized for presentations
- **Graphics**: TikZ-based mathematical visualizations

### Educational Content
- **AI/ML Focus**: Examples and applications relevant to machine learning
- **Interactive Elements**: Exercises and problems for student engagement
- **Visual Learning**: Geometric interpretations and diagrams
- **Progressive Complexity**: Building from basic concepts to advanced topics

### Technical Features
- **Modular Structure**: Separate files for different topics
- **Clean Code**: Well-documented LaTeX source
- **Error-Free Compilation**: Tested and validated syntax
- **Extensible**: Easy to add new sections or modify existing content

## Getting Started

### Prerequisites
- LaTeX distribution (TeX Live, MiKTeX, or MacTeX)
- Required packages:
  - `beamer`
  - `tikz`
  - `amsmath`, `amsfonts`, `amssymb`
  - `geometry`
  - `hyperref`
  - `graphicx`

### Compilation
```bash
# Compile the main presentation
pdflatex main_redesigned_clean.tex

# For bibliography support (if needed)
bibtex main_redesigned_clean
pdflatex main_redesigned_clean.tex
pdflatex main_redesigned_clean.tex
```

### Quick Start
1. Clone or download the repository
2. Ensure all LaTeX packages are installed
3. Compile `main_redesigned_clean.tex` for the modern version
4. The PDF will be generated in the same directory

## Content Sections

### 1. Motivation (`motivation.tex`)
- Mathematical foundation for AI/ML
- Real-world applications
- Industry relevance

### 2. Vectors (`vectors_innerp_norms.tex`)
- Inner products and dot products
- Vector norms (L1, L2, L∞)
- Distances and angles
- Statistical properties
- Cauchy-Schwarz and other inequalities
- Orthogonality and orthonormality
- Gram-Schmidt algorithm

### 3. Matrices (`matrices_definitions.tex`)
- Basic definitions and operations
- Special matrices (identity, symmetric, orthogonal)
- Matrix properties for ML
- Linear systems and applications
- Matrix multiplication visualizations

### 4. Linear Transformations (`linear_transformations_definitions.tex`)
- Definition and properties
- Matrix representations
- Geometric interpretations
- Examples and exercises

## Customization

### Adding New Content
1. Create a new `.tex` file for your section
2. Include it in the main file using `\input{filename}`
3. Follow the existing frame structure and styling

### Modifying Design
- Edit `preamble_modern.tex` for styling changes
- Modify color definitions in the preamble
- Adjust TikZ settings for graphics

### Exercise Integration
- Use the existing exercise format
- Include solutions in separate frames or documents
- Add interactive elements as needed

## Mathematical Notation

The presentation uses standard mathematical notation:
- Vectors: lowercase bold letters (e.g., **a**, **b**)
- Matrices: uppercase bold letters (e.g., **A**, **B**)
- Norms: `\|x\|` for vector norms
- Inner products: `a^T b` or `⟨a,b⟩`
- Angles: `∠(a,b)`

## Dependencies and Packages

### Core Packages
```latex
\usepackage{amsmath,amsfonts,amssymb}
\usepackage{tikz}
\usepackage{geometry}
\usepackage{hyperref}
\usepackage{graphicx}
```

### TikZ Libraries
```latex
\usetikzlibrary{arrows,decorations.pathmorphing,backgrounds,positioning}
```

## Contributing

### Guidelines
1. Maintain consistent notation and style
2. Include examples with AI/ML relevance
3. Add appropriate exercises and problems
4. Test compilation before submitting changes
5. Document new features or sections

### Adding Exercises
- Use clear problem statements
- Include step-by-step solutions
- Reference relevant theorems or concepts
- Provide geometric intuition where applicable

## Educational Philosophy

This presentation follows these pedagogical principles:
- **Conceptual Understanding**: Emphasize geometric intuition
- **Practical Relevance**: Connect theory to AI/ML applications
- **Progressive Learning**: Build complexity gradually
- **Active Engagement**: Include exercises and examples
- **Visual Learning**: Use diagrams and visualizations

## Applications in AI/ML

The content specifically addresses linear algebra applications in:
- **Neural Networks**: Matrix operations in forward/backward propagation
- **Optimization**: Gradient descent and matrix calculus
- **Dimensionality Reduction**: PCA, SVD applications
- **Computer Vision**: Image processing and transformations
- **Natural Language Processing**: Vector embeddings and similarity
- **Machine Learning**: Regression, classification, and model theory

## License

This educational material is designed for academic use at AMMI and related educational institutions.

## Author

Created for the African Masters of Machine Intelligence (AMMI) program.

## Support

For questions or issues:
1. Check LaTeX compilation errors first
2. Verify all required packages are installed
3. Review the modular structure for content organization
4. Refer to LaTeX and Beamer documentation for advanced customization

---

*This presentation aims to provide a solid mathematical foundation for AI/ML students while maintaining practical relevance and visual appeal.*
