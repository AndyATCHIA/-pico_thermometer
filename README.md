# 🌡️ Digital Thermometer with Raspberry Pi Pico W and MicroPython

This project consists of building a **digital thermometer** using the **Raspberry Pi Pico W** and its **built-in temperature sensor**. The data is read in real-time using MicroPython and displayed on a website hosted directly by the Pico W's built-in web server.

## 🔧 Required Hardware

- 1 × Raspberry Pi Pico W  
- Micro-USB cable  
- A computer with Thonny or any MicroPython-compatible editor  
- Wi-Fi connection

## 🧠 Features

- Temperature reading using the Pico W's internal sensor  
- Embedded local web server to display the data  
- Automatic refresh of the temperature on the web page  
- Simple and responsive web interface

## 📦 Project Structure

```

thermometer-web/
├── main.py               # Main MicroPython script
├── web\_page.html         # HTML content served by the web server
├── README.md             # Project documentation

````

## 💡 Usage

1. **Set up Thonny:**  
   - Select "MicroPython (Raspberry Pi Pico)" as the interpreter.  
   - Connect the Pico W to your PC via USB.  

2. **Connect to Wi-Fi:**  
   In `main.py`, update the following lines with your Wi-Fi credentials:

   ```python
   ssid = 'Your_SSID'
   password = 'Your_Password'


3. **Upload the files:**

   * Transfer `main.py` and `web_page.html` to the Pico W.
   * Restart the board if needed.

4. **Access the thermometer:**

   * Once connected to Wi-Fi, the Pico W will display its IP address in the console.
   * Open a web browser and enter this IP to access the website.

## 🌐 Example Output

The web page displays the current temperature detected by the Pico W and updates automatically every 5 seconds.


