# Pantri

Pantri is a backend application built using Python and TypeScript. This project aims to provide a robust and scalable backend solution for managing pantry items and related functionalities.

## Project Structure

```
pantri-backend
├── src
│   ├── python
│   │   ├── main.py          # Entry point for the Python application
│   │   ├── config.py        # Configuration settings for the application
│   │   ├── models           # Directory for data models
│   │   │   └── __init__.py
│   │   ├── services         # Directory for business logic services
│   │   │   └── __init__.py
│   │   ├── utils            # Directory for utility functions
│   │   │   └── __init__.py
│   │   └── requirements.txt  # Python dependencies
│   └── typescript
│       ├── app.ts          # Entry point for the TypeScript application
│       ├── controllers      # Directory for controllers
│       │   └── index.ts
│       ├── routes           # Directory for route definitions
│       │   └── index.ts
│       └── types            # Directory for TypeScript types
│           └── index.ts
├── package.json             # npm configuration file
├── tsconfig.json            # TypeScript configuration file
├── .gitignore               # Files and directories to ignore in version control
└── README.md                # Project documentation
```

## Getting Started

To get started with the Pantri application, follow these steps:

1. **Clone the repository:**
   ```
   git clone <repository-url>
   cd pantri-backend
   ```

2. **Set up Python environment:**
   - Create a virtual environment:
     ```
     python -m venv venv
     ```
   - Activate the virtual environment:
     - On Windows:
       ```
       venv\Scripts\activate
       ```
     - On macOS/Linux:
       ```
       source venv/bin/activate
       ```
   - Install dependencies:
     ```
     pip install -r src/python/requirements.txt
     ```

3. **Set up TypeScript environment:**
   - Install npm dependencies:
     ```
     npm install
     ```

4. **Run the application:**
   - For Python:
     ```
     python src/python/main.py
     ```
   - For TypeScript:
     ```
     npm start
     ```

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License. See the LICENSE file for details.