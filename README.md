# LambdaTest
This project show how to move from a very verbose implementation of a converter, to a compact implementation using lambdas.

The aim is to convert an object of type "Flight" to a JSON string;
we want to be able to have two different convertions, that are:
- put in the JSON only the flight code
- put in the JSON all the (three) fields of the flight

Here are the steps:
- **Main1**: uses two dedicated classes SimpleConverter and FullConverter
- **Main2**: SimpleConverter and FullConverter share a common FlightConverter interface
- **Main3**: uses anonymous inner classes: SimpleConverter and FullConverter are not longer needed  🎉 

