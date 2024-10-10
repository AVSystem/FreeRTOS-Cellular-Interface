# AVSystem adaptation of FreeRTOS Cellular Interface for ESP IDF

This is AVSystem fork of FreeRTOS Cellular Interface v1.2.0 published [here](https://github.com/FreeRTOS/FreeRTOS-Cellular-Interface/tree/v1.2.0).

## Usage Example

Follow [ESP32 with BG96 and FreeRTOS cellular library](https://github.com/AVSystem/Anjay-esp32-client?tab=readme-ov-file#esp32-with-bg96-and-freertos-cellular-library) to see FreeRTOS Cellular Interface for ESP IDF usage example.

## Sources

This project, in addition to being a fork of the `FreeRTOS Cellular Interface`, also relies on slightly modified files from the following projects:

[Free RTOS Cellular Demo](https://github.com/FreeRTOS/Lab-Project-FreeRTOS-Cellular-Demo)<br>
 * `cellular_config.h`<br>
 * `cellular_platform.c`<br>
 * `cellular_platform.h`<br>
 * `cellular_setup.c`<br>
 * `logging_levels.h`<br>
 * `logging_stack.h`<br>

[FreeRTOS-Plus](https://github.com/FreeRTOS/FreeRTOS/tree/202112.00/FreeRTOS-Plus/Source/Application-Protocols/network_transport/sockets_wrapper/cellular)<br>
 * `sockets_wrapper.c`<br>
 * `sockets_wrapper.h`<br>

`cellular_comm_interface.c` was written based on Sanjay Abraham [code](https://github.com/santaseleucid/anjay-esp32-cellular)
