# F1_Project

# ABOUT

Abu Dhabi 2021, last race of the season. Vestappen and Hamilton, Formula 1 drivers are fighting for the title of World Champion. They face each other at the Yas Marina circuit, both with 369.5 points. Hamilton is fighting for his eighth world championship title, surpassing Michael Schumacher's record number of victories, while Max Verstappen is fighting for his first world championship title.  There can only be one winner, which will be decided on the last lap of the final circuit of the season.

This ETL project analyzes the most relevant data of the Abu Dhabi 2021 race, both external such as driver, car, position or result information, as well as detailed data of the fight between Hamilton and Verstappen, specifically on their last lap, by printing the telemetry of both cars.

# PREQUISITES

⭐️ Installation of F1 Race Traces database 

⭐️ Installation of fastf1 library

⭐️ Installation of webdriver-manager

 # SET UP
 
🏁 Import F1 libraries

🏁 Import pandas, Numpy

🏁 Import Seaborn

🏁 Import Matplotlib

🏁 Import of f1 database (CSV)

🏁 Import warnings

🏁 Import functools

🏁 Import requests

🏁 Import time

 # STEP BY STEP
 
✔️ CSV database import

👀 Scraping and obtaining the missing information through Selenium, making use of more than three sources of information

📝 Transformation of the obtained data into DataFrames

💻 Exporting of the scraped DataFrames to CSV

🌍 Data exploration and column correction

🧹 Data and column cleaning

⚡️ Final export to SQL

⚙️ Creation of relations between the different DataFrames in SQL

<img width="973" alt="Captura de Pantalla 2022-11-14 a las 16 38 48" src="https://user-images.githubusercontent.com/29893993/201776500-5bcb7c6a-4bb2-4650-af08-ae05de906276.png">

🌈 Obtain information using Queries

 # TELEMETRY ANALYSIS
 

🌪 Study of the fastest lap in Qualy 




<img width="655" alt="Fastest_lap_qualy" src="https://user-images.githubusercontent.com/29893993/201777933-fcaf0547-9dfa-4083-8a02-8eb8a85caeb5.png">




🌪 Visualization of the fastest lap in Qualy (Verstappen)




<img width="419" alt="fastes_lao_ver_qualy" src="https://user-images.githubusercontent.com/29893993/201778300-8755fe63-2da9-4315-bbf0-93a1ccdb2e95.png">




🏎 Visualization of the average fast lap speed comparison between Hamilton and Verstappen in Qualy




<img width="454" alt="fast_lap_ver y ham_qualy" src="https://user-images.githubusercontent.com/29893993/201779005-e2fbfff2-6c70-40dc-b419-400ad7c5a919.png">




🏁 Visualization of the fastest lap of the race (Verstappen)




<img width="423" alt="fastest_lap_ver_race" src="https://user-images.githubusercontent.com/29893993/201778581-659c6a45-caaf-463e-802f-9354bd4393d1.png">




⚡️ Visualization of average fast lap speed comparison between Hamilton and Verstappen in race




<img width="454" alt="ver_ham_fast_lap_race" src="https://user-images.githubusercontent.com/29893993/201779224-f48f087c-2560-4766-8b33-1ca33a32568c.png">




👀 Visualization of lap comparison between Verstappen and Hamilton




<img width="468" alt="vueltas_ham_ver" src="https://user-images.githubusercontent.com/29893993/201779513-1dd3149c-6620-4678-8aa8-8243b01ad8ce.png">




✨ Display comparison of laps between Hamilton and Sainz



<img width="468" alt="ham_sainz_laps" src="https://user-images.githubusercontent.com/29893993/201779646-04075dfb-4c55-4ee6-bbf0-00c02f5f70b9.png">




🌪 Hamilton fast lap visualization




<img width="551" alt="ham_fastest_lap" src="https://user-images.githubusercontent.com/29893993/201779807-b1895df6-67e8-41cf-8e83-e1a8d3edef76.png">




🌪 Verstappen fast lap visualization




<img width="552" alt="ver_fastest_lap" src="https://user-images.githubusercontent.com/29893993/201779953-7a8abbfd-7cc0-4e9a-881a-1fe66bbd5d15.png">




🔥 Alonso fast lap visualization




<img width="544" alt="ALO_fastest_lap" src="https://user-images.githubusercontent.com/29893993/201780053-f961de9d-6ab2-447d-b688-115b9af21d7d.png">




🌡 Sainz fast lap visualization




<img width="544" alt="Sai_fastest_lap" src="https://user-images.githubusercontent.com/29893993/201780203-28dfabd5-0f1d-4c25-b975-e91701c4efd3.png">




🏁 Visualization of the first Sting comparison between Hamilton and Verstappen




<img width="484" alt="sting" src="https://user-images.githubusercontent.com/29893993/201780378-9223cad4-8988-4734-a877-3bc606754df5.png">




🏎 Visualization of the comparison of traces, brakes and acceleration between Hamilton and Verstappen on the last lap


<img width="443" alt="Captura de Pantalla 2022-11-14 a las 23 23 26" src="https://user-images.githubusercontent.com/29893993/201780690-8c66cafb-90b1-46e1-bca2-9dd0914a9b40.png">

