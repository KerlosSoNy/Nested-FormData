# Nested FormData

`Nested-FormData` is a Function designed to handle nested form data structures in a simplified and efficient way. It helps in managing complex form data, making it easier to work with forms that require hierarchical data.

## Features

- **Nested Form Data Handling**: Easily manage and manipulate nested form data.
- **Flat and Hierarchical Data Structures**: Convert between flat and nested data structures seamlessly.
- **Validation Support**: Integrate with validation libraries to ensure data integrity.
- **Customizable**: Tailor the library to meet specific needs of your form data structures.

## Installation

You can Clone the function via:
```bash
git clone https://github.com/KerlosSoNy/Nested-FormData.git
```
## **Usage**

Basic Usage

Here's a simple example 
```bash
import { appendToFormData } from "./AppendFormData";


const nestedData = {
    user: {
        name: 'John Doe',
        address: {
            street: '123 Main St',
            city: 'Anytown',
        },
    },
};

let formData = new FormData();

// Convert nested data to FormData
formData = appendToFormData(formData, nestedData);
```


## Contributing
If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.

2. Create a new branch for your feature or bugfix.

3. Make your changes and commit them.

4. Push your branch and open a pull request.


## Acknowledgments

TypeScript , DataStructure
