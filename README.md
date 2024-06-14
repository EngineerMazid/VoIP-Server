# VoIP-Server

VoIP-Server is a SIP server application that allows you to create a VOIP server on a mobile device.

https://github.com/EngineerMazid/VoIP-Server/assets/152702183/0ed529bb-fb88-49f3-966e-c3f52bda4f53

## Quick Start Guide

### Example Use Case with CSipSimple as SIP Client

Follow these steps to get started:

1. **Configure uSipServer Properties**:
   - **Domain**: Set this to the SIP server domain. The default value is the local IP.
   - **Local IP**: Set the listening address for SIP messages. The default value is `0.0.0.0 (any)`.
   - **Local Port**: Set the listening port for SIP messages. The default value is `5060`.

2. **Start uSipServer App**:
   - Launch the uSipServer app on your mobile device.
   - Push the `[start]` button to start the server.

3. **Logging Options**:
   - **SIP Log**: Check this box to display SIP signal logs.
   - **Register Log**: Check this box to display REGISTER/UNREGISTER logs.

### Example Use Case with CSipSimple

Here's how you can use the VoIP-Server with the CSipSimple client:

1. Install and configure CSipSimple as your SIP client.
2. Set the server domain and port to match the settings configured in the uSipServer app.
3. Initiate calls and handle SIP messages using CSipSimple, with the uSipServer managing the SIP server functionality.

## Contact

For any issues or support, please contact the developer at [booncraft.com@gmail.com](mailto:booncraft.com@gmail.com).
