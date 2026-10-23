# The-Astronomy-Files
The Astronomy Files is the astro-pocket friend!!
<img width="506" height="507" alt="image" src="https://github.com/user-attachments/assets/5191b77b-3986-49ff-be77-05751f9d6409" />

It aims to liven up the mood with astro-quotes and space-themed cases with our logo. All the colour schemes are chosen to be psychologically attractive and pleasing to the eyes and to soothe the mind.

BOM TAKEN FROM WHERE I INITIALLY HAD IT.
PART	QTY	UNIT	TOTAL	VENDOR	Actions
ESP-32
Primary MCU. Handles deep-sleep and Wi-Fi NTP/API quote fetching.
1	$6.30	$6.30	Espessif	
Real-time Clock
Keeps time tracking accurate to ±2 minutes per year, even if the main battery dies.
1	$10.43	$10.43	Digikey	
Battery Charger
Standard open-source friendly chip to safely manage 3.7V LiPo charging via USB.
1	$3.99	$3.99	Amazon	
Voltage Regulator
Steps down battery voltage to a stable 3.3V for the ESP32 and E-Paper panel.
1	$0.24	$0.24	Mouser Electronics UK	
Display Panel
Zero-power static state. Connects via SPI interface. Main screen.
1	$6.00	$6.00	The Pi Hut	
3.7V 500mAh LiPo Cell
Slim profile battery packed under the PCB board inside the pocket case.
1	$1.99	$1.99	Amazon	

<img width="1706" height="909" alt="Screenshot 2026-10-23 at 11 39 25" src="https://github.com/user-attachments/assets/3a74cfae-4827-470c-ae70-0e8580a8fd49" />


The Astronomy Files operates as an ultra-low-power, standalone astronomical companion by leveraging the dual-core processing and Wi-Fi/Bluetooth capabilities of the ESP32-S3-MINI-1 to calculate real-time celestial coordinates, lunar phases, and target visibility.
To achieve extreme energy efficiency for long field sessions, the system utilizes a high-precision DS3231 RTC for accurate timekeeping while the main microcontroller enters deep sleep, waking only at defined intervals to pull precise satellite/time data and update the 1.54-inch E-Paper display.
Onboard power management—driven by an AP2112K 3.3V LDO regulator and an integrated TP4056 LiPo charging circuit—ensures stable, continuous operation from a 3.7V battery source while maintaining full visibility under direct sunlight with zero static power draw from the screen.
