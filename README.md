
# UserFinder Tool

![UserFinder](https://i.imgur.com/b1Graiv.png)

![Result](https://i.imgur.com/fo9xFXh.png)

UserFinder is a simple command-line tool that allows you to check the availability of a username on various online platforms. It provides an easy way to see if your desired username is already taken on popular social media sites, websites, and more.

## Features

- Check the availability of a username on multiple platforms.
- Easily navigate through the menu-based interface.
- Get information about the tool and its creator.

## Installation

1. Clone this repository or download the ZIP file.

2. Navigate to the project directory in your terminal.

3. Install the required dependencies using npm:

   ```bash
   npm install
   ```

## Usage

To start UserFinder, run the following command:

```bash
npm start
```

This will launch the tool and display the main menu. From there, you can select various options:

1. **Check Username Availability:** Enter the username you want to check, and UserFinder will search for it on multiple platforms.

2. **About:** Get information about the tool and its creator.

3. **Exit:** Quit the tool.

### Using the API

You can also use an API to check the availability of a username. Here is the API endpoint:

```
https://links.sergappteknologi.my.id/username.php?username=rasitech
```

Replace `rasitech` with the username you want to check. The API will return a response indicating whether the username is available or not.

## Customization

You can customize the list of URLs to check by editing the `urlList` array in the `usernameChecker.mjs` file. Add or remove URLs based on the platforms you want to check.

## Dependencies

UserFinder relies on the following npm packages:

- [axios](https://www.npmjs.com/package/axios): For making HTTP requests.
- [chalk](https://www.npmjs.com/package/chalk): For colorizing terminal output.
- [figlet](https://www.npmjs.com/package/figlet): For displaying the tool's title in ASCII art.

## License

This project is licensed under the MIT License. Feel free to use and modify it for your needs.

## About the Creator

UserFinder was created by [@RasiTechChannel](https://t.me/RasiTechChannel1) and is maintained by [support@rasitechchannel.my.id]. You can find more of my projects on my GitHub profile.

If you have any questions or suggestions, feel free to contact me at [support@rasitechchannel.my.id].
```
