# Nature-Inspired Storage & Computing

An interactive educational website exploring DNA-based data storage and digital information systems. The project demonstrates how binary data can be encoded into DNA sequences, decoded back into usable files, and visualized in an intuitive, biology-inspired interface.

Live demo: https://dna-encoder-decoder.vercel.app

## Overview

This project brings together several concepts in a single browser-based experience:

- DNA encoding for text and files
- DNA decoding from ATCG sequences back into original data
- Binary-to-DNA mapping and visual explanation of the conversion process
- Alternative no-repeat encoding mode inspired by DNA storage research
- Animated DNA double helix visualization
- Educational slides explaining the idea, motivation, and principles behind DNA data storage

## Features

### DNA Encoder
- Encode plain text into readable DNA code
- Upload files and estimate how they would be stored in DNA
- Explore conversion from bytes to binary to DNA bases
- Compare direct 2-bit mapping with no-repeat encoding strategies
- View file size, nucleotide count, GC content, and repeat-risk estimates

### DNA Decoder
- Paste a DNA sequence in ATCG format
- Decode back to original text, images, or file content
- Auto-detect or manually select encoding scheme
- Visualize the step-by-step transformation from base pairs to bytes

### Learning Experience
- Presentation-style slides explaining DNA storage concepts
- Interactive helix-based visualizations for easier understanding
- Supports practical examples and research-inspired explanation

## Project Structure

```text
.
├── DNA_Encoder_Decoder/
│   ├── index.html
│   ├── favicon.png
│   ├── pfp/
│   └── slides/
└── README.md
```

## Local Usage

Because this project is a static HTML/CSS/JavaScript site, you can run it locally in either of these ways:

### Option 1: Open directly in a browser
- Open `DNA_Encoder_Decoder/index.html` in your browser.

### Option 2: Run a local server
```bash
cd dna-encoder-decoder
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000/DNA_Encoder_Decoder/
```

## Why This Project Matters

Traditional storage media like HDDs and SSDs are reaching physical and practical limits. DNA offers a biologically inspired alternative with extremely high information density and long-term archival potential. This project helps explain that concept in an accessible, interactive way.

## Team

This project was created by students exploring the intersection of biology and computer engineering:

- Harshal Chikkote
- Manas Kesarkar
- Shivam Kumar

## License

This project is currently shared for educational and demonstration purposes.

## References

The project is inspired by research in DNA data storage, including work on:

- DNA-based digital information storage
- Synthetic DNA as a storage medium
- Error-tolerant and high-capacity encoding schemes

## Contact

For questions or collaboration opportunities, feel free to explore the project repository or connect through the project’s live demo.
