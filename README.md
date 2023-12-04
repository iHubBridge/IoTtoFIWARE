# IoTtoFIWARE
Starting by the FIWARE Zone Tutorial :"https://github.com/FIWAREZone/iot_curse"

This Tutorial intent to show the use of a real IoT device the ESP8266 node and a continuity of the FIWARE Tutorial "https://www.fiware.org/2015/06/10/iot-tutorial-orion-context-broker-arduino/"

The Internet of Things (IoT) is a network of physical devices which are able to connect to a network and exchange data. Each "thing" or "smart device" is a gadget with embedded electronics and software which can act as a sensor or actuator. Sensors are able to report the state of the real-world around them. Actuators are responsible for altering the state of the system, by responding to a control signal.

Each device is uniquely identifiable through its embedded computing system but is able to interoperate within the existing internet infrastructure.

FIWARE is a system for managing context information. For a smart solution based on the internet of Things, the context is provided by the array of attached IoT devices. Since each IoT device is a physical object which exists in the real world, it will eventually be represented as a unique entity within the context.

IoT devices can range from simple to complex. Here are some examples of IoT devices which will be used within this tutorial:

A Smart Door is an electronic door which can be sent commands to be locked or unlocked remotely. It can also report on its current state (OPEN, CLOSED or LOCKED),
A Bell can be sent a command to activate and ring for a short period
A Motion Sensor will activate and send a count when someone is nearby
A Smart Lamp can be switched on or off remotely. It can also report on its current state (ON or OFF). When switched on, a Motion Sensor within the device checks to see if light is needed and will dim if no-one is nearby. Furthermore the device can be report on the output state and input of each GPIO (General Purpose Input Output).
As you can see, the Bell is an example of a pure actuator, as it only reacts to the given commands. Meanwhile, the Motion Sensor is an example of a pure sensor, since it will only report on the state of the world as it sees it. The other two GPIO are able to both respond to the commands and report on state in a meaningful way.

The state information held within each device, as it will eventually be seen within the Context Broker is defined in the diagram below:
![entities image](https://github.com/iHubBridge/IoTtoFIWARE/blob/main/entities.png)


