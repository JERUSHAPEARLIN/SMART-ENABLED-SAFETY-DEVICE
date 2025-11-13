**Project Title:**

    IoT-Enabled Safety Device Using Arduino Nano

**Brief Description:**

      The IoT-enabled safety device is a smart emergency alert system designed to ensure personal safety in critical or dangerous situations. The system allows a person in distress to send an alert message along with their real-time location to a predefined mobile number at the press of a button.

      The project uses an Arduino Nano as the main controller, which integrates multiple modules — a Neo-6M GPS module to detect the person’s geographical location, a SIM900A GSM module to send an SMS alert, and an RF (R433) module for short-range wireless communication. A push button is used as the trigger to initiate the emergency alert, and a Li-ion battery powers the entire system.

      When the button is pressed, the Arduino collects the GPS coordinates from the GPS module and sends an SMS message through the GSM module, such as “Emergency! Come fast! Location: [latitude, longitude]”. The RF module simultaneously transmits a wireless alert signal that can be received by nearby devices for quick response.

      This device can be worn or carried by individuals, making it ideal for women’s safety, elderly monitoring, and personal security applications. It ensures that help can reach the person in need quickly, even in remote areas where immediate communication is critical.

**Key Features:**

    Instant SMS alert through GSM module.
    
    Wireless RF communication for local alerts.
    
    Compact and portable design using Arduino Nano.
    
    Battery-powered for field use.
