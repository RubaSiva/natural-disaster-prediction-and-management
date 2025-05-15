# Landslide Prediction Web Application

This project is a web-based application that predicts the probability of a landslide occurring based on user inputs. The app utilizes Materialize CSS for a modern and responsive design.

---

## Features

* User-friendly interface for inputting data.
* Predict landslide probability based on soil/rock type, slope angle, and water content.
* Real-time prediction using backend processing.
* Responsive design powered by Materialize CSS.

---

## Technologies Used

### Frontend

* **HTML**: For structuring the web page.
* **CSS**: Materialize CSS framework for styling.
* **JavaScript**: For client-side functionality and interaction.

### Backend

* **Python**: Backend logic using the Eel library to connect the web interface with Python.
* **Eel**: Lightweight Python library for building web-based GUI applications.

---

## Setup Instructions

### Prerequisites

1. Install Python (3.6 or higher).
2. Install pip (Python package manager).

### Steps

1. Clone this repository:

   ```
   git clone https://github.com/your-repo/landslide-prediction.git
   cd landslide-prediction
   ```
2. Install required Python packages:

   ```
   pip install eel
   ```
3. Run the application:

   ```
   python app.py
   ```
4. Open a browser and navigate to `http://127.0.0.1:5000`.

---

## Usage

1. Enter the following inputs in the web interface:

   * **Soil/Rock Type**: Specify the type of soil or rock.
   * **Slope Angle**: Enter the slope angle in degrees.
   * **Water Content**: Provide the water content percentage.

2. Click the `PREDICT PROBABILITY` button.

3. View the prediction result displayed below the form.

---

## Project Structure

```
project-directory
|-- app.py            # Main Python script to run the application
|-- /static
    |-- eel.js         # Eel integration for Python-JS communication
|-- /templates
    |-- index.html     # Main web interface
|-- README.md          # Project documentation
```

---

## Acknowledgments

* **Materialize CSS**: For the responsive and beautiful front-end framework.
* **Eel Library**: Simplifies the process of connecting Python and JavaScript.

---

## License

This project is licensed under the MIT License. Feel free to use and modify as needed.

---

## Support

If you encounter any issues or have questions, feel free to open an issue in the repository or contact the development team.

---

Happy predicting! \:rocket:

# natural-disaster-prediction-and-management
