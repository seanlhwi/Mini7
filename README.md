# Mini7
A macro pad style custom drum pad with seven keys. This idea first reached me after yearning to try a drum set, but also wanted it to be portable. After pondering on what device type to use, I came across electronical drum pads, where each drum is practically a switch. It was at this moment when I thoguht about making the electronical drum set out of MX switches! Each of my keys are a different drum type, consisting of a base drum, high tom, mid tom, low tom, snare drum, hi-hat, and ride cymbal. Other key details are the battery monitoring screen and satisfying push button on/off button. The software was written on Aurduino IDE, and it is in a binary format to be flashed on a RP2040 Zero. Instead of just creating a box shape, the bottom two corners are cut to create a more interesting design. This project is easily recreatable by simply assemblying all of the parts according to the schematic and flashing the firmware. I hope to extend this drum system by making other types of drums too. <img width="1126" height="638" alt="Screenshot 2026-07-18 at 11 07 57 PM" src="https://github.com/user-attachments/assets/fe3fb8b2-484b-45f5-823c-bc4b606f71ea" />
<img width="1087" height="713" alt="Screenshot 2026-07-18 at 11 07 19 PM" src="https://github.com/user-attachments/assets/6ed905ed-dd86-4c63-9dcc-94ad8afeacc4" />
<img width="1447" height="886" alt="Screenshot 2026-07-08 at 5 41 50 PM" src="https://github.com/user-attachments/assets/a8811cf8-4c92-4178-a8d9-9e5e92a8b938" />
# Mini7 Bill of Materials

| Name | Purpose | Quantity | Total (USD) | Link | Distributor |
|------|---------|----------|-------------|------|--------------|
| PCB | PCB | 5 | $10.40 | [View](https://cart.jlcpcb.com/shopcart/cart) | JLCPCB |
| Super Glue | Gluing | 1 | $2.72 | [View](https://www.aliexpress.us/item/3256808473825074.html) | Ali Express |
| MAX17048 Module | Battery monitor | 1 | $5.95 | [View](https://www.adafruit.com/product/5580) | Adafruit |
| Push Button | On/Off | 1 | $6.99 | [View](https://www.amazon.com/Cylewet-Self-Locking-Latching-Button-CYT1091/dp/B075VBV4QH) | Amazon |
| N52 Magnets | Securing Case | 10 | $2.56 | [View](https://www.aliexpress.us/item/3256810556183287.html) | Ali Express |
| 400mAh LiPo Battery | Battery | 1 | $8.99 | [View](https://www.amazon.com/Battery-Rechargeable-Lithium-Polymer-Connector/dp/B09F9W7Z6J) | Amazon |
| 0.91" OLED Screen | Battery Display | 2 | $5.99 | [View](https://www.amazon.com/Dorhea-Display-SSD1306-Arduino-3-3V-5V/dp/B07FMDB6TR) | Amazon |
| PCM5102A Module | Audio Output | 1 | $3.64 | [View](https://www.aliexpress.us/item/3256806642863761.html) | Ali Express |
| Tenstar RP2040 Zero | MCU | 2 | $5.19 | [View](https://www.aliexpress.us/item/3256806637247373.html) | Ali Express |
| TP4056 Module | Charging Unit | 1 | $1.39 | [View](https://www.aliexpress.us/item/3256808777213556.html) | Ali Express |
| 10 µF Capacitor | Capacitor | 50 | $3.10 | [View](https://www.aliexpress.us/item/3256807278239101.html) | Ali Express |
| 100nF Capacitor | Capacitor | 50 | $0.00 (Bundle) | [View](https://www.aliexpress.com/ssr/300001493/welcomegiftspmpc?productIds=1005007470747384) | Ali Express |
| 4.7k Resistors | Resistor | 1 | $2.88 | [View](https://www.aliexpress.com/ssr/300001493/welcomegiftspmpc?productIds=1005007470747384) | Ali Express |

## Totals

| Metric | Value |
|--------|-------|
| Total Number of Items | 13 |
| Total Number of Parts | 126 |
| **Total Cost** | **$59.80** |
