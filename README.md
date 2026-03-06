# Electrolyseur-ESPHOME-RS485
Control electrolyseur avec un ESP32 en liaison modbus

Code avec un ESP32 C6 , mais peut être utilisé avec tout type d'ESP32 , il faut adapter le type de carte utilisée dans board:

Valable sur la plus part des électrolyseur ayant une entrée accessible en modbus : Racer , Ibiza , Majestic , DuoSalt ..

Entre l'electrolyseur et l'ESP32 , j'ai un convertisseur standard TTL vers 485 uart :
Alim en +5V et GND 
Tx vers A et Rx vers B , si pas de com inverser A et B suivant l'electroseur
GND du coté A et B relié au GND de l'electrolyseur

La majorité des électrolyseurs ont une table d'échange modbus similaire pour les adresses de type température , electrolyse , pH ...
Les autres adresses sont à adapter en fonction du modèle utilisé 


<img width="796" height="1145" alt="HA" src="https://github.com/user-attachments/assets/ab519428-f402-4076-921e-94eb43b0f852" />
