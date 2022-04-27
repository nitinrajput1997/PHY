# PHY
So far, we have contructed transport block which includes both data and control element.

**NOTE:** So now , the job of physical layer is to transmit the transport block over the wireless channel as efficiently as possible.

PHYSICAL-Layer does this by Modulation, Coding, Multi-Antenna processing and by mapping the signals to the appropriate physical time and frequency resources.

The physical channel mainly handles the mapping of the transport channel to the physical channel.

Physical-Channel is defien by 'set of time-frequency resources used for transmission of a particular transport channel'.

It includes DCI (downlink control information) which provides the devices with necessary information for proper reception and decoding of downlink data.

It aslo includes UCI (uplink control information) which provides the scheduler on the hybrid ARQ protocol with the information about the situation at the device .

Different types of physical channel:-

1. PBCH - This carries the system information that the device can use to access the network.
2. PDSCH - This is the main channel for data transmission to tghe devices for paging information and also for delivering part of system information.
3. PDCCH - This is used for downlink control information like scheduling decision.
4. PUSCH - This is the main channel for data transmission from device side.
5. PUCCH - This is used by the user equipment for hybrid ARQ acknowlegement indicating whether you recieved a trnsport block successfully or unsuccessfully.
6. PRACH - This is used for random Access Procedures
