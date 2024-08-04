---

# Pascal's Triangle Algorithm in Python

## Overview

This project implements Pascal's Triangle using Python. Pascal's Triangle is a triangular array of binomial coefficients, named after Blaise Pascal. In this implementation, we generate the first `n` rows of Pascal's Triangle.

## Table of Contents

- [Pascal's Triangle Algorithm in Python](#pascals-triangle-algorithm-in-python)
  - [Overview](#overview)
  - [Table of Contents](#table-of-contents)
  - [Features](#features)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Example Output](#example-output)
  - [Contributing](#contributing)
  - [License](#license)
  - [Contact](#contact)

## Features

- Generates Pascal's Triangle up to the specified number of rows.
- Simple and efficient algorithm implementation.
- Easy to integrate and use in other projects.

## Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/chipatenii/0x00-pascal_triangle.git
   ```
2. **Navigate to the Project Directory:**
   ```bash
   cd 0x00-pascal_triangle
   ```

3. **Create a Virtual Environment (optional but recommended):**
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

4. **Install Required Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
   (Note: If there are no dependencies, you can skip this step.)

## Usage

To generate Pascal's Triangle, you can run the `0-pascal_triangle.py` script:

```bash
python 0-pascal_triangle.py
```

You can also import the `0-pascal_triangle.py` function in your own scripts:

```python
from pascals_triangle import generate_pascals_triangle

# Generate the first 5 rows of Pascal's Triangle
rows = generate_pascals_triangle(5)
print(rows)
```

## Example Output

Here is an example output for generating the first 5 rows of Pascal's Triangle:

```
[
 [1],
 [1, 1],
 [1, 2, 1],
 [1, 3, 3, 1],
 [1, 4, 6, 4, 1]
]
```

## Contributing

We welcome contributions! If you have suggestions for improvements, please follow these steps:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature-branch`.
3. Make your changes and commit them: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature-branch`.
5. Submit a pull request.

Please ensure your code follows the project's coding standards and includes appropriate tests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any inquiries or feedback, please contact:

Innocent  Manda  
Email: innocentmanda70@gmail.com

---
