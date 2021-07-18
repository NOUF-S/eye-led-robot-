# eye-led-robot-


An arduino-circuit to control the robot eyes. It uses PWM to reduce the energy losses in the LEDs.
We connected the LEDs in parallel so if one got open, the other eye is not affected.    Series Connection: The eye led is connected in series. The most efficient way to run high power LEDs is using a series circuit with a constant current LED driver. Running a series circuit helps to provide the same amount of current to each LED. This means each LED in the circuit will be the same brightness and will not allow a single LED to hog more current than another. When each LED is receiving the same current it helps eliminate issues like thermal runaway What is an LED driver you might ask? An LED driver is an electrical device that regulates power to an LED or a string of LEDs. It is a crucial piece to an LED circuit and to operate without one will result in system failure

#  circuit

![eye led robot circuit](https://user-images.githubusercontent.com/86829538/126076417-e1cc3e81-61b8-4c7d-90c9-32b8c0a583d6.png)

https://www.tinkercad.com/things/2sxi9inj1Vk-frantic-gaaris-bojo/editel?sharecode=FfR3ALLomlE5bYd2gkDKKhV-gnk0_jlfsCFeCqm6wgY

# code 

//
void setup()
{

  pinMode(5, OUTPUT);
}


void loop()
{

  digitalWrite(5, HIGH);
 
}
