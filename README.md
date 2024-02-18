# Backend Workshop

Welcome to the Backend Workshop! This repository contains instructions and code for setting up and running the backend server for a workshop project.

## Instructions to Run

Follow these steps to set up and run the backend server:

### 1. Create a Python Environment

First, create a Python virtual environment using the following command:

```bash
python -m venv myenv
```

### 2. Activate the Python Environment

Activate the Python environment based on your operating system:

- **Mac**:
  ```bash
  source myenv/bin/activate
  ```

- **Windows CMD**:
  ```bash
  myenv\Scripts\activate.bat
  ```

- **Windows PowerShell**:
  ```bash
  myenv\Scripts\Activate.ps1
  ```

### 3. Install Flask

Once the environment is activated, install Flask using pip:

```bash
pip install Flask
```

### 4. Start the Backend Server

Navigate to the `back-end` directory and start the backend server by running `app.py`:

```bash
cd back-end
python app.py
```

## Additional Notes

Ensure that you have Node.js and npm installed on your system before proceeding.

### Starting React

If you also need to start the React frontend, follow these additional steps:

### 1. Install Dependencies

Navigate to the `front-end` directory and install the necessary dependencies:

```bash
cd front-end
npm install
```

### 2. Start React Server

After installing dependencies, start the React server:

```bash
npm start
```

## Contributors

- Jeanie Ho
- Jatin Kulkarni
- Matt Tolea
- Dylan Tse

Feel free to contribute by submitting pull requests or opening issues. We appreciate your feedback and contributions!