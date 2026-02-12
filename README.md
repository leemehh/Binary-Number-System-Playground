#  Binary & Number System Playground

A web-based interactive tool to visualize how numbers are represented in computers. Explore base conversions, signed integers, and IEEE-754 floating point representations with clear step-by-step explanations.

---

## Features

### Base Converter
Convert numbers between Decimal, Binary, and Hexadecimal.  
- Input a value in any supported base.
- Get instant results in all three bases.
- Handles decimal, binary (with or without spaces), and hexadecimal (with or without `0x` prefix).

### Step-by-Step Conversion
See how decimal numbers are converted to binary:  
- Enter a positive integer.
- Get a detailed division-by-2 breakdown.
- Visualize the calculation of remainders from LSB to MSB.

### Signed Integers (8-bit)
Analyze signed integers using three common representations:  
- **Sign-Magnitude**
- **One's Complement**
- **Two's Complement**
- Visualize the 8-bit binary structure, including MSB (sign bit) and LSB.

### IEEE-754 Floating Point (32-bit)
Understand floating-point representation:  
- Input any decimal number (positive or negative).
- Visualize the 32-bit binary structure:
  - 1 Sign bit
  - 8 Exponent bits (with bias 127)
  - 23 Mantissa bits
- See the computed formula and resulting decimal value.

---

## Demo

Open `index.html` in a modern browser to try it live.  

---

## Technologies Used
- **HTML5** – Structure and semantic markup
- **CSS3** – Modern dark-themed styling and responsive layout
- **JavaScript (ES6)** – Dynamic calculations, visualizations, and interactive features

---

## Usage

1. Open `index.html` in any modern browser.
2. Use the **Base Converter** to convert numbers between decimal, binary, and hexadecimal.
3. Use **Step-by-Step Conversion** to understand how decimal numbers are converted to binary.
4. Use **Signed Integers** to explore 8-bit integer representations.
5. Use **IEEE-754 Floating Point** to see how decimal numbers are represented in memory.

---

## Code Structure

- **Base Converter** – `convertNumber()` handles parsing and conversion between bases.
- **Step-by-Step Conversion** – `showSteps()` generates and displays binary conversion steps.
- **Signed Integers** – `showSigned()` calculates sign-magnitude, one's complement, and two's complement.
- **IEEE-754 Float Visualization** – `showFloat()` extracts the sign, exponent, and mantissa of a 32-bit float.

---

## Styling

- Dark-themed design for comfortable viewing.
- Syntax-inspired monospace fonts.
- Color-coded bits for MSB, LSB, exponent, and mantissa.
- Responsive layout using flexbox for cards and input groups.

---

## Notes
- Only integers between -128 and 127 are supported for signed integer analysis.
- Floating point analysis uses JavaScript `Float32Array` to mimic IEEE-754 behavior.
- Step-by-step conversion is limited to positive integers.

---

## License
MIT License – feel free to use, modify or distribute.
