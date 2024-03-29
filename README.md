@iliciuv author: Miguel Garcia-Duch v.1.0 17-Oct-2023

# Async-ModubusTCP Streamlit WebApp
Minimal implementation of an asyncronous modbus web-client for getting readings from TCP devices.

It has been built using streamlit which allows a really easy implementation of a user interface for asyncmodbus in a single file app of around 100 lines of code.

## Modificable Parameters:
    - host: Modbus server IP address.
    - port: Modbus server port.
    - address: Starting address for reading.
    - register_length: Number of registers to read.
    - data_type: Data type for conversion. One of "int16", "uint16", "int32", "uint32", "uint32_alt", "float".

### Live example in share.streamlit.io:

-----------------------------------

https://webmodbusclient.streamlit.app/

-----------------------------------
