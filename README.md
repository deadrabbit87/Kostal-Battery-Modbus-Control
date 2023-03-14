# Kostal-Battery-Modbus-Control
disables discharging the battery while charging the EV. 

Node RED 3.0.2 is used. 

Reads the charging plan from evcc.io via REST API. If the vehicle is charging, discharging from the home battery is disabled via Modbus Register 1034 of a Kostal Plenticore Inverter. 

Only usefull in combination with a flexible tariff like tibber or awattar. Due to this, energy in the battery is available for powering the home in the morning hours. 
