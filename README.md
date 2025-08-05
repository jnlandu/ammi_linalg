# AMMI 2025 Course Materials

This repository contains lecture materials and presentations  I gave (during my stay as tutor) for the African Masters of Machine Intelligence (AMMI) 2025 bootcamp. The materials are designed to provide a solid foundation in mathematics and programming for AI and machine learning.

## What's Inside

### Linear Algebra (`linalg/`)
A comprehensive introduction to linear algebra concepts essential for machine learning:
- Vector spaces, operations, and norms
- Matrix operations and transformations
- Eigenvalues and eigenvectors
- Matrix decompositions (QR, SVD, Cholesky)
- Linear transformations and projections

### Python Fundamentals (`python/`)
Complete Python programming course from basics to data science:
- Python syntax and fundamentals
- Data types and control structures
- Functions and object-oriented programming
- NumPy for numerical computing
- Pandas for data manipulation
- Matplotlib for visualization
- Scikit-learn for machine learning
- Best practices and debugging

### Advanced Python (`python_partb/`)
Extended Python topics for advanced applications (work in progress).

### Introduction to PyTorch (`intro2pytorch/`)
Introduction to deep learning fundamentals using PyTorch framework (work in progress).

## Getting Started

### Prerequisites
- LaTeX distribution (TeX Live, MiKTeX, or MacTeX)
- PDF viewer
- Basic familiarity with command line (optional)

### Compiling the Materials
Each course folder contains a `main.tex` file that compiles into a complete presentation:

```bash
cd linalg/
pdflatex main.tex
# or
cd python/
pdflatex main.tex
```

The presentations use modern Beamer themes with AIMS branding and include:
- Interactive code examples
- Mathematical visualizations with TikZ
- Exercise sections
- Clean, professional styling

## Course Structure

The materials are organized as modular LaTeX presentations that can be:
- Used as lecture slides
- Compiled into comprehensive textbooks
- Referenced as individual topic guides

<!-- Each section is self-contained but builds upon previous concepts, making it easy to follow the learning progression or jump to specific topics. -->

## Planned Additions

We're actively working on expanding this repository with additional course materials:

- **PyTorch**: Deep learning fundamentals and neural network implementation
- **TensorFlow**: Alternative deep learning framework coverage
- **Advanced Statistics**: Probability theory and statistical inference
- **Optimization**: Mathematical optimization for machine learning
- **Computer Vision**: Image processing and computer vision applications
- **Natural Language Processing**: Text processing and NLP techniques

## Contributing

If you find errors, have suggestions, or want to contribute additional materials:
1. Fork this repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

I welcome contributions that improve the educational value of these materials.

## Usage Notes

### For Instructors
- Make full use of the materials
- There is no need to acknowledge the source, but appreciated.


### For Students

- Materials progress from beginner to intermediate level
- Each section includes practical exercises
- Code examples can be copied and modified
- Additional resources are referenced throughout


## Technical Details

### Dependencies
The LaTeX materials use several packages for enhanced presentations:
- `beamer` for presentations
- `tikz` for mathematical diagrams
- `listings` for code highlighting
- `fontawesome5` for modern icons
- Custom AIMS color schemes and styling

### Compilation
All materials have been tested/compiled  with:
- TeX Live 2023+
- pdfLaTeX engine
- Standard LaTeX packages
- VScode

## License

I wrote these materials for myself( for later references), for futur AMMI students, and  for everyone outside there would them useful. 

Make full use of the materials, adapt them for your needs, and share them with others. Attribution is appreciated but not required.

## Contact

For questions about the materials or suggestions for improvement, please open an issue or reach out to me [here](https://jmabiala.com).

