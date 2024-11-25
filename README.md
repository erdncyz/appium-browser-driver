# Appium Browser Driver

Appium Browser Driver is a custom driver for [Appium](https://appium.io/) designed to simplify browser automation for end-to-end testing of web and mobile applications.

## 🚀 Features
- Support for multiple browsers.
- Easy integration with existing Appium setups.
- Configuration options for various test environments.
- Lightweight and efficient design.

---

## 🛠️ Installation

### Install `template-driver` aka `custom-driver` (if not installed)

To install the driver, run:

```sh
appium driver install --source npm appium-driver-template

📚 Usage

Run Appium Server with Custom or Template Driver
To run the Appium server using this driver, execute:

appium server -pa /wd/hub --use-drivers=<<driver-name>>
Replace <<driver-name>> with the name of your installed driver.

General Steps to Use

1. Clone the repository:

git clone https://github.com/erdncyz/appium-browser-driver.git
cd appium-browser-driver

2. Install dependencies:
npm install

3.Run the driver:

npm start

4.Configure your Appium server to use this driver as shown above.

🧪 Running Tests
To execute tests, use:

npm test

Ensure you have the required test dependencies installed and your environment configured properly.

📄 License
This project is licensed under the MIT License. See the LICENSE file for details.

🖋️ Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository.
2. Create a new branch:
git checkout -b feature/your-feature-name
3. Commit your changes:
git commit -m "Add your feature"
4. Push the branch:
git push origin feature/your-feature-name
5. Create a Pull Request.



🙌 Acknowledgments
Appium
Open-source contributors

Made with ❤️ by erdncyz