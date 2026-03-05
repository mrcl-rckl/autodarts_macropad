<div align="center">
    <img src="https://github.com/mrcl-rckl/autodarts_macropad/blob/main/readme-images/Rendering.png?raw=true" alt="3D-Modell" width="800">
  
  <h1>🎯 Macropad for Autodarts</h1>
  <p><b>✨ The ultimate DIY wireless companion for your Autodarts setup ✨</b></p>
  <p><i>A custom 12-key controller designed for seamless darts tracking.</i></p>

  <p>
    The Macropad for Autodarts is a wireless DIY controller featuring 12 mechanical keys, specifically designed for comfortable operation of the Autodarts software directly from the oche. It provides instant access to functions such as undoing throws, switching cameras, or calling the AI referee, while offering an impressive battery life of about six weeks via Bluetooth. Thanks to its open-source firmware, the entire device is fully customizable to suit your personal needs.
  </p>

  <p>
    <img src="https://img.shields.io/badge/Difficulty-Experienced_Makers-orange.svg?style=for-the-badge&logo=buildkite" alt="Difficulty" />
    <img src="https://img.shields.io/badge/Hardware-nRF52840-lightgrey.svg?style=for-the-badge&logo=nordicsemiconductor" alt="Hardware" />
    <img src="https://img.shields.io/badge/Firmware-ZMK-blue.svg?style=for-the-badge&logo=github" alt="Firmware" />
  </p>

  <p>
    <a href="#features-en">🚀 Features</a> •
    <a href="#manual-en">📖 Manual</a> •
    <a href="#diagrams-en">🗺️ Wiring & Pinout</a> •
    <a href="#keymap-en">🎹 Keymap</a> •
    <a href="#bom-en">📦 BOM</a> •
    <a href="#operation-en">💡 Troubleshooting</a> •
    <a href="#support-en">☕ Support</a>
  </p>
</div>

<hr />

<h2 id="features-en">🚀 Key Features</h2>
<ul>
  <li><b>📶 True Wireless:</b> Low-energy Bluetooth 5.0 connectivity via the nRF52840 controller for a cable-free oche. 🎯</li>
  <li><b>🔋 Massive Battery Life:</b> Operates for up to <b>6 weeks</b> on a single charge. The integrated deep-sleep mode further preserves battery life. ⚡</li>
  <li><b>⌨️ Superior Tactile Feedback:</b> 12 mechanical Gateron G Pro 3.0 switches provide a high-quality actuation point for reliable inputs. ⌨️</li>
  <li><b>☁️ Cloud Configuration:</b> Customize your keymap directly in the browser via GitHub Actions—no local coding environment required. ☁️</li>
  <li><b>🖥️ OS Integration:</b> Battery percentage is reported natively and can be viewed in Windows or Linux system settings. 🖥️</li>
</ul>

<hr />

<h2 id="manual-en">📖 Comprehensive Manual</h2>
<p>
  This repository includes a <b>detailed 32-page PDF instruction manual</b>. It covers the entire process: from optimized 3D printing settings and complex matrix soldering to flashing the ZMK firmware and customized key mapping.
  <br><br>
  👉 <b>View the Instructions here:</b> <a href="https://github.com/mrcl-rckl/autodarts_macropad/blob/main/instructions/0_EN_Instructions.pdf">0_EN_Instructions.pdf</a>
  <br>
  👉 <b>3D Models on Printables:</b> <a href="https://www.printables.com/model/1576041-autodarts-macropad">Printables.com</a>
  <br>
  👉 <b>3D Models on MakerWorld:</b> <a href="https://makerworld.com/de/models/2319788-autodarts-macropad">MakerWorld.com</a>
</p>

<hr />

<h2 id="bom-en">📦 Bill of Materials (BOM)</h2>
<p>This project is designed for experienced makers and involves 3D printing, component assembly, and precision soldering. 🛠️</p>
<table>
  <thead>
    <tr>
      <th>Qty</th>
      <th>Component 🛒</th>
      <th>Source 🔗</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>12x</td>
      <td><b>Gateron G Pro 3.0 Switches</b></td>
      <td><a href="https://de.aliexpress.com/item/1005007052507996.html">AliExpress</a></td>
    </tr>
    <tr>
      <td>1x</td>
      <td><b>nRF52840 Developer Board (SuperMini)</b></td>
      <td><a href="https://de.aliexpress.com/item/1005008664621573.html">AliExpress</a></td>
    </tr>
    <tr>
      <td>1x</td>
      <td><b>500mAh LiPo Battery (503030)</b></td>
      <td><a href="https://de.aliexpress.com/item/1005007964712378.html">AliExpress</a></td>
    </tr>
    <tr>
      <td>12x</td>
      <td><b>1N4148 Diodes</b></td>
      <td><a href="https://de.aliexpress.com/item/1005006208000285.html">AliExpress</a></td>
    </tr>
    <tr>
      <td>16x</td>
      <td><b>Jumper Wires Female (20-30cm)</b></td>
      <td><a href="https://de.aliexpress.com/item/1005007046465880.html">AliExpress</a></td>
    </tr>
    <tr>
      <td>1x</td>
      <td><b>Toggle Switch (MTS-101)</b></td>
      <td><a href="https://de.aliexpress.com/item/1005009744920784.html">AliExpress</a></td>
    </tr>
    <tr>
      <td>1x</td>
      <td><b>ASUS USB-BT500 Bluetooth Dongle</b></td>
      <td><a href="https://www.cyberport.de/pc-und-zubehoer/netzwerk/bluetooth/asus/pdp/4e18-007/asus-usb-bt500-bluetooth-5-0-usb-adapter.html">Cyberport</a></td>
    </tr>
  </tbody>
</table>

<h3>🛠️ Required Tools & Additional Materials</h3>
<ul>
  <li>USB-C charging cable</li>
  <li>Soldering iron & Solder wire</li>
  <li>Hot air gun or lighter (for insulation)</li>
  <li>Heat shrinks & side cutters</li>
  <li>Pliers & wire stripping tool</li>
  <li>Super glue (for mounting logos)</li>
  <li>Filament (PLA or PETG - 2 colors recommended)</li>
</ul>

<hr />

<h2 id="diagrams-en">🗺️ Wiring Diagram & Pinout</h2>
<div align="center">
  <h3>🛠️ Wiring Diagram</h3>
  <img src="https://github.com/mrcl-rckl/autodarts_macropad/blob/main/readme-images/0_Wiring_Diagram.png?raw=true" alt="Wiring Diagram" width="800">
  <br><br>
  <h3>🔌 Controller Pinout</h3>
  <img src="https://github.com/mrcl-rckl/autodarts_macropad/blob/main/readme-images/0_Pin_Diagram.png?raw=true" alt="Pin Diagram" width="800">
</div>

<hr />

<h2 id="keymap-en">🎹 Default Key Assignment</h2>
<p>The layout is fully optimized for the Autodarts web interface commands. 🎯</p>

<div align="center">
  <img src="https://github.com/mrcl-rckl/autodarts_macropad/blob/main/readme-images/0_Key_Assignment.png?raw=true" alt="Keymap Assignment" width="800">
</div>

<div align="center">
  <img src="https://github.com/mrcl-rckl/autodarts_macropad/blob/main/readme-images/0_Quick_Correction.png?raw=true" alt="Quick Correction" width="800">
</div>

<div align="center">
  <img src="https://github.com/mrcl-rckl/autodarts_macropad/blob/main/readme-images/0_Settings.png?raw=true" alt="Settings" width="800">
</div>

<br>

<hr />

<h2 id="operation-en">💡 Operation & Troubleshooting</h2>
<ul>
  <li><b>Charging:</b> The physical toggle switch <b>MUST be in the ON position</b> to charge the battery via USB-C. 🔌</li>
  <li><b>Pairing Reset:</b> To clear existing Bluetooth bonds, press <b>[Arrow Left] + [Arrow Right]</b> keys simultaneously twice. 🔄</li>
  <li><b>Bootloader Mode:</b> If the device is not recognized as a drive, bridge the <b>GND</b> and <b>RST</b> pins twice quickly while connected to the PC. 💾</li>
  <li><b>Input Focus:</b> Ensure the browser window is "in focus" (clicked) for Autodarts to register key presses. 🎯</li>
</ul>

<hr />

<h2 id="support-en">☕ Support</h2>
<p align="left">
  If this project helped you hit the bullseye, consider supporting my work! 🎯☕
  <br><br>
  <a href="https://www.buymeacoffee.com/mrcl_rckl">
    <img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" height="50" width="210" alt="Buy Me A Coffee" />
  </a>
</p>

<hr />
<br><br>
<div style="height: 15px; background: linear-gradient(90deg, #444 0%, #888 50%, #444 100%); border-radius: 8px; margin: 50px 0;"></div>
<br><br>
<hr />

<div align="center">
  <h1>🎯 Zusatztastatur für Autodarts</h1>
  <p><b>✨ Der ultimative kabellose Begleiter für dein Autodarts-Setup – Marke Eigenbau ✨</b></p>
  <p><i>Ein maßgeschneidertes 12-Tasten-Steuergerät für die professionelle Wurferfassung am Oche.</i></p>

  <p>
    Das Macropad für Autodarts ist ein kabelloses DIY-Steuergerät mit 12 mechanischen Tasten, das speziell für die komfortable Bedienung der Autodarts-Software direkt am Oche entwickelt wurde. Es ermöglicht den blitzschnellen Zugriff auf Funktionen wie Wurfrücknahme, Kamerawechsel oder den KI-Schiedsrichter und bietet dank Bluetooth-Anbindung eine beachtliche Akkulaufzeit von etwa sechs Wochen. Durch die Nutzung von Open-Source-Firmware lässt sich das gesamte Gerät zudem vollständig nach deinen persönlichen Wünschen anpassen.
  </p>

  <p>
    <img src="https://img.shields.io/badge/Schwierigkeit-Erfahrene_Maker-orange.svg?style=for-the-badge&logo=buildkite" alt="Schwierigkeit" />
    <img src="https://img.shields.io/badge/Hardware-nRF52840-lightgrey.svg?style=for-the-badge&logo=nordicsemiconductor" alt="Hardware" />
    <img src="https://img.shields.io/badge/Firmware-ZMK-blue.svg?style=for-the-badge&logo=github" alt="Firmware" />
  </p>

  <p>
    <a href="#features-de">🚀 Funktionen</a> •
    <a href="#manual-de">📖 Anleitung</a> •
    <a href="#diagrams-de">🗺️ Schaltplan & Pinbelegung</a> •
    <a href="#keymap-de">🎹 Tastenbelegung</a> •
    <a href="#bom-de">📦 Stückliste</a> •
    <a href="#operation-de">💡 Fehlerbehebung</a> •
    <a href="#support-de">☕ Unterstützung</a>
  </p>
</div>

<hr />

<h2 id="features-de">🚀 Hauptmerkmale</h2>
<ul>
  <li><b>📶 Vollkommen Kabellos:</b> Dank Bluetooth 5.0 und dem nRF52840-Steuermodul bleibt dein Abwurfbereich frei von Kabeln. 🎯</li>
  <li><b>🔋 Enorme Akkulaufzeit:</b> Eine einzige Ladung hält bei normaler Nutzung bis zu <b>6 Wochen</b>. Der integrierte Tiefschlafmodus schont die Batterie zusätzlich. ⚡</li>
  <li><b>⌨️ Hochwertiger Druckpunkt:</b> 12 mechanische Gateron G Pro 3.0 Schalter bieten ein erstklassiges haptisches Feedback und garantieren eine zuverlässige Bedienung. ⌨️</li>
  <li><b>☁️ Cloud-Konfiguration:</b> Die Tastenbelegung kann direkt im Browser über GitHub-Automatisierungen angepasst werden – es ist keine lokale Programmierumgebung erforderlich. ☁️</li>
  <li><b>🖥️ System-Integration:</b> Der Akkustand wird direkt in den Einstellungen von Windows oder Linux angezeigt. 🖥️</li>
</ul>

<hr />

<h2 id="manual-de">📖 Umfangreiche Anleitung</h2>
<p>
  In diesem Projektarchiv findest du eine <b>detaillierte 32-seitige PDF-Anleitung</b>. Diese führt dich Schritt für Schritt durch den gesamten Prozess: von den optimalen Einstellungen für den 3D-Druck über das präzise Verlöten der Tastatur-Matrix bis hin zur Installation der Steuersoftware und der persönlichen Tastenbelegung.
  <br><br>
  👉 <b>Hier zur Anleitung:</b> <a href="https://github.com/mrcl-rckl/autodarts_macropad/blob/main/instructions/0_DE_Anleitung.pdf">0_DE_Anleitung.pdf</a>
  <br>
  👉 <b>3D-Modelle auf Printables:</b> <a href="https://www.printables.com/model/1576041-autodarts-macropad">Printables.com</a>
  <br>
  👉 <b>3D-Modelle auf MakerWorld:</b> <a href="https://makerworld.com/de/models/2319788-autodarts-macropad">MakerWorld.com</a>
</p>

<hr />

<h2 id="bom-de">📦 Stückliste</h2>
<p>Dieses Projekt wird für erfahrene Bastler empfohlen, da es fundierte Kenntnisse im 3D-Druck und im Weichlöten voraussetzt. 🛠️</p>
<table>
  <thead>
    <tr>
      <th>Menge</th>
      <th>Bauteil 🛒</th>
      <th>Bezugsquelle 🔗</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>12x</td>
      <td><b>Gateron G Pro 3.0 Tastenschalter</b></td>
      <td><a href="https://de.aliexpress.com/item/1005007052507996.html">AliExpress</a></td>
    </tr>
    <tr>
      <td>1x</td>
      <td><b>nRF52840 Entwickler-Platine (SuperMini)</b></td>
      <td><a href="https://de.aliexpress.com/item/1005008664621573.html">AliExpress</a></td>
    </tr>
    <tr>
      <td>1x</td>
      <td><b>500mAh LiPo Akku (Bauform 503030)</b></td>
      <td><a href="https://de.aliexpress.com/item/1005007964712378.html">AliExpress</a></td>
    </tr>
    <tr>
      <td>12x</td>
      <td><b>1N4148 Dioden</b></td>
      <td><a href="https://de.aliexpress.com/item/1005006208000285.html">AliExpress</a></td>
    </tr>
    <tr>
      <td>16x</td>
      <td><b>Steckbrückenkabel (weiblich, 20-30cm)</b></td>
      <td><a href="https://de.aliexpress.com/item/1005007046465880.html">AliExpress</a></td>
    </tr>
    <tr>
      <td>1x</td>
      <td><b>Kippschalter (MTS-101)</b></td>
      <td><a href="https://de.aliexpress.com/item/1005009744920784.html">AliExpress</a></td>
    </tr>
    <tr>
      <td>1x</td>
      <td><b>ASUS USB-BT500 Bluetooth-Adapter</b></td>
      <td><a href="https://www.cyberport.de/pc-und-zubehoer/netzwerk/bluetooth/asus/pdp/4e18-007/asus-usb-bt500-bluetooth-5-0-usb-adapter.html">Cyberport</a></td>
    </tr>
  </tbody>
</table>

<h3>🛠️ Erforderliche Werkzeuge & Materialien</h3>
<ul>
  <li>USB-C Ladekabel</li>
  <li>Lötkolben & Lötzinn</li>
  <li>Heißluftfön oder Feuerzeug (für die Isolierung der Kontakte)</li>
  <li>Schrumpfschläuche & Seitenschneider</li>
  <li>Zange & Abisolierwerkzeug</li>
  <li>Sekundenkleber (zum Fixieren der Logos)</li>
  <li>Filament (PLA oder PETG - 2 verschiedene Farben für Kontrast-Optik empfohlen)</li>
</ul>

<hr />

<h2 id="diagrams-de">🗺️ Stromlaufplan & Anschlussbelegung</h2>
<div align="center">
  <h3>🛠️ Schaltplan der Tastatur-Matrix</h3>
  <img src="https://github.com/mrcl-rckl/autodarts_macropad/blob/main/readme-images/0_Schaltplan.png?raw=true" alt="Stromlaufplan" width="800">
  <br><br>
  <h3>🔌 Anschlussbelegung des Steuerungsmoduls</h3>
  <img src="https://github.com/mrcl-rckl/autodarts_macropad/blob/main/readme-images/0_Pin_Diagram.png?raw=true" alt="Anschlussbelegung" width="800">
</div>

<hr />

<h2 id="keymap-de">🎹 Standard-Tastenbelegung</h2>
<p>Die Tasten sind für die Autodarts-Weboberfläche optimiert, damit du dich voll auf deine Würfe konzentrieren kannst. 🎯</p>

<div align="center">
  <img src="https://github.com/mrcl-rckl/autodarts_macropad/blob/main/readme-images/0_Tastenbelegung.png?raw=true" alt="Tastenbelegung" width="800">
</div>

<div align="center">
  <img src="https://github.com/mrcl-rckl/autodarts_macropad/blob/main/readme-images/0_Schnell-Korrektur.png?raw=true" alt="Schnell-Korrekur" width="800">
</div>

<div align="center">
  <img src="https://github.com/mrcl-rckl/autodarts_macropad/blob/main/readme-images/0_Einstellungen.png?raw=true" alt="Einstellungen" width="800">
</div>

<br>

<hr />

<h2 id="operation-de">💡 Bedienung & Fehlerbehebung</h2>
<ul>
  <li><b>Ladevorgang:</b> Der physische Kippschalter <b>MUSS auf EIN (ON)</b> stehen, damit der Akku über USB-C geladen werden kann. 🔌</li>
  <li><b>Verbindung zurücksetzen:</b> Um die Bluetooth-Kopplung zu löschen, die Tasten <b>[Pfeil Links] + [Pfeil Rechts]</b> gleichzeitig zweimal drücken. 🔄</li>
  <li><b>Bootloader-Modus:</b> Falls die Platine nicht als Laufwerk erkannt wird, überbrücke kurz zweimal hintereinander die Kontakte <b>GND</b> und <b>RST</b>. 💾</li>
  <li><b>Eingabe-Fokus:</b> Das Browserfenster muss aktiv sein („im Fokus“), damit Autodarts die Tastaturbefehle registriert. 🎯</li>
</ul>

<hr />

<h2 id="support-de">☕ Unterstützung</h2>
<p align="left">
  Hat dieses Projekt bei dir ins Schwarze getroffen? Wenn du meine Arbeit unterstützen möchtest, freue ich mich über einen digitalen Kaffee! Jeder Beitrag fließt direkt in die Entwicklung neuer Prototypen und quelloffener Werkzeuge für die Community. 🎯☕
  <br><br>
  <a href="https://www.buymeacoffee.com/mrcl_rckl">
    <img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" height="50" width="210" alt="Spende mir einen Kaffee" />
  </a>
</p>
