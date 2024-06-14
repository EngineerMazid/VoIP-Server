# VoIP-Server

VoIP-Server is a SIP server application that allows you to create a VOIP server on a mobile device.

![about_usipserver_0](https://github.com/EngineerMazid/VoIP-Server/assets/152702183/8446e68d-8784-44d0-bfc9-b3deeaae29fa)


## Quick Start Guide

![scrshot_authcon_1](https://github.com/EngineerMazid/VoIP-Server/assets/152702183/7aa8f306-e15f-40e9-9864-df5e528b66b7)
![scrshot_qs_4](https://github.com/EngineerMazid/VoIP-Server/assets/152702183/a6cd2c48-37b2-4284-a515-ab956eb0ae4d)
![_20240614_161856_uSipServer](https://github.com/EngineerMazid/VoIP-Server/assets/152702183/65a6a331-0fd6-4590-bc17-634dbb3cc211)
![_20240614_161905_uSipServer](https://github.com/EngineerMazid/VoIP-Server/assets/152702183/d8e3f874-9265-4209-91c0-0ebf76a4862c)
![20240614_161919_uSipServer](https://github.com/EngineerMazid/VoIP-Server/assets/152702183/beb08edd-8503-4aa6-8ec1-417e4e882601)


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
