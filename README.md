## Fault Identification in Distribution Feeder with PV using CNN code

Fault detection and isolation is critical for reliable
operation of distribution systems. The ride-through requirements
for the distributed energy resources (DER), mandated
by the IEEE 1547-2018 standard, makes it challenging to use
undervoltage (UV) conditions for fault detection. In addition,
with low fault current contribution from these inverter-based
DERs, the time-overcurrent relays are also less effective. In this repository a learning-based approach for
fault detection and localization is presented. A convolutional neural network
(CNN)-based model is proposed which uses local voltage and
current waveforms from DER locations and feeder substations,
for training a zonal classifier. The classifier can be adopted into
any relay-like device for discriminating between faults originating
from different protection zones. The performance of the proposed
approach was tested on publicly available test feeders with
distributed photovoltaics (PVs).
