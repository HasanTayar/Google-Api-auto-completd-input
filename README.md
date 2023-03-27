# PHP Google Autocomplete Address Example

This is a PHP application that uses the Google Places API to provide autocomplete suggestions for addresses and locations.

## Getting Started

To use this application, you'll need to obtain a Google Places API key. You can get a key by following these steps:

1. Go to the [Google Cloud Console](https://console.cloud.google.com/).
2. Create a new project or select an existing project.
3. In the sidebar, click on "APIs & Services" and then "Credentials".
4. Click on "Create credentials" and select "API key".
5. Copy the API key and replace `YOUR_API_KEY` in `GoogleAutoComplete.php` with your own key.

After obtaining an API key, you can clone or download this repository to your local machine:

git clone https://github.com/HasanTayar/Google-Api-auto-completd-input.git

Next, navigate to the project directory and open `GoogleAutoComplete.php`. Replace `YOUR_API_KEY` with your own Google Places API key.

Finally, you can start a local server and view the application in a web browser:

php -S localhost:8000

This will start a server and make the application available at `http://localhost:8000`.

## Usage

Once the application is running, you can use it to search for addresses and locations. Simply enter a search term in the input field and select a suggestion from the dropdown. The latitude and longitude for the selected location will be displayed in the corresponding input fields.

## Contributing

If you'd like to contribute to this project, please fork the repository and create a pull request with your changes.
## Running the project using WAMP

Download and install WAMP.
Clone or download the project from GitHub.

Move the project files to the www folder inside the WAMP installation folder. The default path is C:\wamp\www.
Start WAMP server by running the wampmanager.exe file from the WAMP installation folder.

Open your web browser and navigate to http://localhost/Google-Api-auto-completd-input/ to view the project.

## Running the project using XAMPP

Download and install XAMPP.

Clone or download the project from GitHub.

Move the project files to the htdocs folder inside the XAMPP installation folder. The default path is C:\xampp\htdocs.
Start XAMPP server by running the xampp-control.exe file from the XAMPP installation folder.

Open your web browser and navigate to http://localhost/Google-Api-auto-completd-input/ to view the project.
## License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.
