# Other Packages required in your workspace are 

# diffdrive_arduino

```bash
https://github.com/attu0/diffdrive_arduino.git
```

This package is being used in ros2 control to control the motors, at this path /dev_ws/src/articubot_one/description/ros2_control.xacro. To define the params to control actuators with ros2 coontrol

# ros_arduino_bridge
```bash
https://github.com/attu0/ros_arduino_bridge.git
```

This package contains the code required to upload on microcntrol(Ardduino UNO), for your particular setup you will be required to set the correct pin to match your setup or you can follow the same. To change pins modify it in 

~/ros_arduino_bridge/ROSArduinoBridge/motor_driver.h  := for motor and l298n setup
~/ros_arduino_bridge/ROSArduinoBridge/encoder_driver.h := for encoders

# serial
```bash
https://github.com/attu0/serial.git
```

this is c++ package used to communicate with arduino serially no changes are required here to make, alternatively you can use pyserial also but that will a diffrenet story

# serial_motor_demo
```bash 
https://github.com/attu0/serial_motor_demo.git
```

this is used to test your motors are in working for the above setup you can igonre this or remove later but its great for debugging.