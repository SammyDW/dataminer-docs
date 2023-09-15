---
uid: Connector_help_Axon_ACP_GXG010
---

# Axon ACP GXG010

The GXG010 is a dual-channel 3 Gb/s, HD up-converter with color corrector and optional cross-input audio shuffler.

The **Axon ACP GXG010** connector can be used to display and configure information related to this device.

## About

This connector can be automatically generated by the connector **Axon ACP Frame Manager**.

There are different possibilities available for **alarm monitoring** and **trending**.

### Version Info

| **Range** | **Key Features**             | **Based on** | **System Impact** |
|-----------|------------------------------|--------------|-------------------|
| 1.0.0.x   | Initial version \[SLC Main\] | \-           | \-                |

### Product Info

| **Range** | **Supported Firmware** |
|-----------|------------------------|
| 1.0.0.x   | 6893, 7499, 7509       |

### System Info

| **Range** | **DCF Integration** | **Cassandra Compliant** | **Linked Components** | **Exported Components** |
|-----------|---------------------|-------------------------|-----------------------|-------------------------|
| 1.0.0.x   | Yes                 | Yes                     | \-                    | \-                      |

## Installation and configuration

### Creation

The element using this connector can be automatically created by the parent element using the **Axon ACP Frame Manager** connector, but it can also be a standalone element.

### Connections

#### Serial Main Connection

This connector uses a serial connection and requires the following input during element creation:

SERIAL CONNECTION:

- Interface connection:

  - **IP address/host**: The polling IP or URL of the destination.
  - **Bus address**: The bus address of the device, being the slot number of the card.

#### Serial Broadcast Connection

This connector uses a serial connection and requires the following input during element creation:

SERIAL CONNECTION:

- Interface connection:

  - **IP address/host**: The polling IP or URL of the destination.
  - **Bus address**: The bus address of the device.

## Usage

The element has the following data pages:

- **General**: This page displays general information about the card: **Card Name**, **Card Description**, **SW Revision**, **HW Revision**, etc.
- **Status**
- **I/O**
- **GPI**
- **Options**
- **Video**
- **Inserter**
- **Transparent**
- **Up Conversion**
- **Down Conversion**
- **Cross Conversion**
- **Embedder**
- **Embedder A**
- **Embedder B**
- **Embedder C**
- **Embedder D**
- **De-Embedder**
- **Network**
- **Alarm Priority**: This page displays the event messages of the card, i.e. special messages generated asynchronously on the card.

## DataMiner Connectivity Framework

The Axon ACP protocol supports the usage of DCF and can only be used on a DMA with **8.5.4** as the minimum version.

DCF can also be implemented through the DataMiner DCF user interface and through DataMiner third-party connectors (for instance a manager).

### Interfaces

#### Physical Interfaces

- **SDI Input**: A single fixed interface of type **input**.
- **REF Input 1**: A single fixed interface of type **input**.
- **REF Input 2**: A single fixed interface of type **input**.
- **SDI Output 1**: A single fixed interface of type **output**.
- **SDI Output 2**: A single fixed interface of type **output**.
- **SDI Output 3**: A single fixed interface of type **output**.
- **SDI Output 4**: A single fixed interface of type **output**.