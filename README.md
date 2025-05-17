# Arduino TinyML Libraries Collection

This repository contains all the necessary libraries required to run TinyML-based human detection applications on the **Arduino Nano 33 BLE Sense** using the **Arducam 2MP Plus** camera module. The libraries have been pre-configured to simplify the setup process and ensure compatibility with the provided software examples.

---

## Included Libraries

- **Arduino_TensorFlowLite**: Enables running TensorFlow Lite Micro models on Arduino-compatible boards.
- **Arducam**: Provides communication support for the Arducam 2MP Plus camera module via SPI and I2C.
- **JPEGDecoder**: Allows decoding JPEG images into raw pixel data formats for image processing tasks.

---

## How to Install

1. **Download the Libraries Package**  
   - Click the green **Code** button above and select **Download ZIP**.  
   - Extract the ZIP file to a location on your computer.

2. **Locate Your Arduino Libraries Folder**  
   - Move the extracted library folders into the following location based on your operating system:

| Operating System | Arduino Libraries Folder Location        |
|------------------|------------------------------------------|
| Windows          | `Documents\Arduino\libraries`            |
| macOS            | `~/Documents/Arduino/libraries`          |
| Linux            | `~/Arduino/libraries`                    |

> **Note:** If the `libraries` folder does not exist, you can create it manually inside the `Arduino` directory.

3. **Verify in Arduino IDE**  
   - Open the Arduino IDE.  
   - Navigate to **Sketch > Include Library > Manage Libraries**.  
   - Confirm that the installed libraries appear under **Contributed Libraries**.

---

## Getting Started with Human Detection

Once the libraries are installed, you can start running the human detection program:

1. Open Arduino IDE and go to **File > Examples > Arduino_TensorFlowLite > person_detection**.
2. Follow the program upload instructions as outlined in the user guide.
3. Enjoy real-time human detection using your Arduino Nano 33 BLE Sense and Arducam 2MP Plus!

---

## Documentation

For detailed setup instructions and troubleshooting, refer to the **End User Guide** and **Technical Guide** provided with the project.

---

## Notes

- Ensure your Arduino IDE is updated to the latest version for full library compatibility.
- If you are using a different model or have a custom machine learning model, additional configuration may be required.

---

## License

This repository is distributed for educational and research purposes. Refer to the LICENSE file for more details if applicable.

---
