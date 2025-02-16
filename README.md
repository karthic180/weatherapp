# Current Weather App

The Current Weather App allows you to retrieve and display the current weather for a specified city using the `wttr.in` API.

## Features
- Fetch current weather information for any city.
- Simple and easy-to-use terminal-based interface.
- Displays weather information in a clean, readable format.

## Technologies Used
- Java
- HTTP requests using `HttpURLConnection`
- JSON response handling via `BufferedReader` and `InputStreamReader`

## Setup and Usage

### Prerequisites
Ensure that you have **Java** installed on your system. If not, download and install Java from the official website:

- [Download Java](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html)

### How to Run
1. Clone the repository or download the `WeatherApp.java` file to your local machine.
2. Open a terminal and navigate to the directory where the `WeatherApp.java` file is located.
3. Compile the Java program using the following command:

   javac WeatherApp.java

4. Run the compiled Java program with the following command:

   java WeatherApp

5. The app will prompt you to enter a city name (e.g., London). After entering the city name, the app will fetch and display the current weather for that city.

### Example Usage:

Enter the city name: London  
Weather in London: Clear 18°C

## License
This project is open-source and available under the [MIT License](LICENSE).

## Contributing
Feel free to fork the repository, create issues, and submit pull requests. Contributions are welcome!

## Acknowledgments
- This app uses the `wttr.in` service for retrieving weather data. Check out [wttr.in](https://wttr.in/) for more information.

---
