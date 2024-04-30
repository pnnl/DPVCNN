The CNN scheme is entirely a data-driven relay. It attempts to identify
the fault just from local current and voltage waveforms. In this project, these were created by
EMT simulation, with the equivalent of a 10-kHz sampling rate. The trained model of a CNN
would be downloaded to the relay, which might be implemented in a real-time automation
controller (RTAC). The CNN training might be updated over time, but otherwise does not
depend on system conditions.
