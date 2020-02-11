# ESP-commander
Command your ESP via webservice


GET http://#ESPIP#/test/
.. returns internal parameters from test() function


POST http://#ESPIP#/configure/

{
  "type":"RELAY  ",
  "pin":5,
  "on":300,
  "off":600,
  "startin":0
}

... configure the ESP scheddule & actions
