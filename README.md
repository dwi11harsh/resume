# LaTeX Resume Template

A clean, professional, and highly customizable LaTeX resume template designed for developers and technical professionals. Features responsive layouts, hyperlink integration, and performance metrics emphasis.



## Features

- **Modern Design**: Clean typography with dark blue accents
- **Hyperlinked Contacts**: Clickable email, LinkedIn, GitHub, etc.
- **Performance Metrics**: Built-in formatting for quantifiable achievements (e.g., `30% faster load`)
- **Responsive Layout**: Optimized spacing for A4 and letter paper
- **Font Options**: 10+ font families included (Helvetica, Times, Palatino, etc.)
- **LaTeX Packages**: Pre-configured with essential packages (`hyperref`, `tabularx`, `enumitem`, etc.)

## Quick Start

1. **Requirements**:

   - LaTeX distribution (TeX Live/MiKTeX/MacTeX)
   - Modern editor (VS Code, Overleaf, or Texmaker)

2. **Basic Usage**:
   ```latex
   \resumeSubheading
       {Company Name}{Location}
       {\underline{Job Title}}{Start Date - End Date}
       \resumeItemListStart
         \item Achievement with metric (e.g., 40\% performance improvement)
         \item \textbf{Stack:} Technologies used
       \resumeItemListEnd
   ```
