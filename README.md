# sphero-bb8-examples

#How to connect to BB8?

#****Code Sample***
var sphero = require("sphero"),
    bb8 = sphero("b5a12bdd4824411691d7fba2799779b9"); //  BLE address for my device BB-1F60

bb8.connect(function() {
  // Your device is connected now. Startdoing cool stuff here.
  
  // Set the color to BB8
  bb8.color({ red: 255, green: 0, blue: 255 });

});

#**********
