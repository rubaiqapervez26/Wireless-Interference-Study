

Project Overview
    This project explores the operational mechanics of the 2.4 GHz ISM band. It demonstrates how controlled RF noise and channel congestion can disrupt wireless communication, highlighting vulnerabilities to Denial of Service (DoS) attacks.

🎯 Objectives:
      Analyze Bluetooth and Wi-Fi behavior under heavy RF interference.
      Establish SPI communication between an ESP32 and nRF24L01 module.
      Study defensive strategies and mitigation techniques for wireless networks.
  
🛠️ Hardware Requirements:
        ESP32-Wroom-32UE (Main Controller).
        nRF24L01+ PA/LNA Antenna Module.
        nRF24L01 Adapter/Protector Module (for stable 3.3V power).
        Push Button, Jumper Wires, and USB Power Supply.
  
💻 Software & Libraries:
      Arduino IDE.RF24 and ezButton Libraries.
      Python (for signal strength visualization).
      
📊 Key FindingsBluetooth:  
          Shows better short-range resilience due to Frequency Hopping Spread Spectrum (FHSS) but still suffers from packet loss under heavy noise.Wi-Fi: Performance degrades significantly faster; latency rises and throughput decreases as channel collisions increase.
      
⚠️ Ethical Disclaimer:
          This project is for educational and research purposes only. Jamming third-party communications is illegal. All tests were conducted in a shielded laboratory environment.
