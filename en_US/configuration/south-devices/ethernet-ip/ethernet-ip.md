# EtherNet/IP(CIP)

EtherNet/IP (Industrial Protocol), developed and maintained by the Open DeviceNet Vendor Association (ODVA), is a pivotal network protocol in industrial automation. It fosters seamless automated control and data exchange between devices, significantly benefiting sectors including manufacturing, energy, transportation logistics, and construction by enhancing operational efficiency and data transparency.

You can use Neuron EtherNet/IP (CIP) plugin to connect EtherNet/IP devices.

## Add Device

Go to **Configuration -> South Devices**, then click **Add Device** to add the driver. Configure the following settings in the popup dialog box.

- Name: The name of this device node.
- Plugin: Select the **EtherNet/IP (CIP)** plugin.

## Device Configuration

After clicking **Create**, you will be redirected to the **Device Configuration** page, where we will set up the parameters required for Neuron to establish a connection with the northbound application. You can also click the device configuration icon on the southbound device card to enter the **Device Configuration** interface.

| Field          | Description                |
| -------------- | -------------------------- |
| PLC IP Address | Device ip                  |
| PLC Port       | Device port, default 44818 |
| CPU Slot       | Cpu slot, default 0        |

## Configure Data Groups and Tags

After the plug-in is added and configured, the next step is to establish communication between your device and Neuron by adding groups and tags to the Southbound driver.

Once device configuration is completed, navigate to the **South Devices** page. Click on the device card or device row to access the **Group List** page. Here, you can create a new group by clicking on **Create**, then specifying the group name and data collection interval.

Upon successfully creating a group, click on its name to proceed to the **Tag List** page. This page allows you to add device tags for data collection. You'll need to provide information such as the tag address, attributes, and data type.

For information on general configuration items, see [Connect to Southbound Devices](../south-devices.md). The subsequent section will concentrate on configurations specific to the driver.

### Data Types

* INT8
* UINT8
* INT16
* UINT16
* INT32
* UINT32
* INT64
* UINT64
* FLOAT
* DOUBLE
* BOOL
* BIT
* STRING
* WORD
* DWORD
* LWORD

### Address Format

>  TAG NAME </span>

Connect to PLC with PLC software, the name of the point on the PLC is the address of the point in Neuron.

## Data Monitoring

After completing the point configuration, you can click **Monitoring** -> **Data Monitoring** to view device information and control devices. For details, refer to [Data Monitoring](../../../usage/monitoring.md).
