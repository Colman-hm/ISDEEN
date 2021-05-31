# ISDEEN
It is a year-long project about exercise gamification. Our final idea is to develop a brand new multiplayer strategy online game with controllers. The code below is for the 3 devices(2 hand controller and 1 leg strap)
For 2 hand module, arduino nano is used, they will transmit the data(IMU, joystick and buttons) to the leg strap through nRF24L01
For the leg strap, ESP32 is used, it will receive data from two hand controller and process, at last will transmit data to the game through bluetooth
