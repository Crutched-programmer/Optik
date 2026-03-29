<h1>Optik</h1> <h3>Minimal Smart Glasses HUD Prototype</h3>
<h2>Overview</h2>

Optik is a lightweight smart glasses prototype that projects basic information into the user’s field of view using a simple optical setup and an OLED display.

The current implementation focuses on a single, stable use case: rendering an analog clock through a heads-up display (HUD) driven by a microcontroller.

This project demonstrates the feasibility of low-cost, DIY wearable display systems using readily available components.

<h2>Features</h2> <ul> <li>Heads-up display (HUD) projection</li> <li>Real-time analog clock rendering</li> <li>OLED-based visual output</li> <li>Microcontroller-driven simulation logic</li> <li>Simple optical reflection system</li> </ul>
<h2>Hardware Stack</h2> <ul> <li>Arduino Mega 2560</li> <li>SSD1306 OLED Display</li> <li>Basic optical reflector setup</li> </ul>
<h2>Software Stack</h2> <ul> <li>C++ (Arduino framework)</li> <li>SSD1306 display drivers</li> <li>Custom clock rendering logic</li> </ul>
<h2>How It Works</h2>

The Arduino Mega initializes a simulated clock starting from 00:00 and continuously updates an analog clock rendered on the OLED display.

The OLED output is positioned behind a reflective surface aligned with the lens, creating a heads-up display effect where the user can view the clock without looking away from their surroundings.

The system prioritizes simplicity and proof-of-concept execution over precision optics.

<h2>Use Case</h2>

This project is an experimental prototype exploring wearable display systems.

It is intended for:

<ul> <li>Understanding HUD design fundamentals</li> <li>Exploring low-cost smart glasses architecture</li> <li>Rapid prototyping of embedded visual systems</li> </ul>
<h2>Current Status</h2> <ul> <li>Working prototype</li> <li>Basic functionality validated</li> <li>Manual optical alignment</li> </ul>
<h2>Demo</h2> <img src="smarglassesdemo.gif" alt="Optik Demo" />
<h2>Limitations</h2> <ul> <li>Bulky optical setup</li> <li>No battery integration</li> <li>No real-time synchronization</li> <li>Limited to a single display function</li> </ul>
<h2>Roadmap</h2> <ul> <li>Use the  ESP32 C3 SuperMini for compact design</li> <li>Integrate battery-powered operation</li> <li>Improve optical alignment and reduce bulk</li> <li>Expand HUD capabilities beyond clock display</li> </ul>
