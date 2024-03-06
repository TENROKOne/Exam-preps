# Describe the benefits and usage of Internet of Things (IoT) Hub, IoT Central, and Azure Sphere

There is some trust within the sensor. to enable end to end securiy use Azure Sphere.

## Azure Spehere
- Focused on End to End Security
- Three options available:
    1. MCU needs to be Azure Spehere Certified
    2. Linux based OS, customized kernel (provides can use this)
    3. AS3 (Azure Shere Sercurity Serivce)
        - Certificate based

## IoT Hub
- Device to Cloud Metric / Telemetry / Request and response
- Device to Cloud Upload
- Cloud to Device (command en control)
- Createas a device twin, who is a representation of the fysical device.
- IOT hub talks to the twin, the fysical devices talks to the twin.

My application talks to the SDK of IOT hub.

## IoT Central
- Uses IoT Hub
- Is a SAAS solution
- Dashboards / Apps
- Device templates (attributes and metrics to expect)
    - Simulated devices
- Commen industry scenarios
- Full customize
- Add rules via a Wizard
    - Signal -> Condition -> Action
        - Send a Email
        - SMS
        - Webhook
        - Function / logic App
        - ITSM

## Summary
When you want something out of te box use IoT Central

When you want to write your own code to the SDK use IoT Hub

When you need end-to-end security use Azure Sphere