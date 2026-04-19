When I first started reading about vehicle navigation security, I 
was surprised by how wide the gap is between how reliable people 
assume GPS to be and how easy it is to manipulate. Most drivers, 
and even many engineers outside the field, tend to treat GPS as a 
solid, trustworthy reference. In reality, the civilian GPS signal is 
unencrypted, arrives at the receiver with a power level of roughly 
−130 dBm (about twenty billion times weaker than a typical Wi-Fi 
signal), and contains no mechanism for the receiver to verify that 
the signal genuinely came from a satellite rather than a transmitter 
sitting on a rooftop nearby. 
Navigation systems have evolved enormously since the first 
commercial GPS receivers appeared in the late 1980s. The Global 
Navigation Satellite System (GNSS) family now includes the 
American GPS, the Russian GLONASS, the European Galileo, and 
the Chinese BeiDou, all of which provide Positioning, Navigation, 
and Timing (PNT) services to billions of users. Modern vehicles 
layer 
additional sensors on top of GNSS-accelerometers, 
gyroscopes, cameras, LiDAR, and radar-and connect to the outside 
world through Bluetooth, Wi-Fi, cellular, and dedicated Vehicle-to
Everything (V2X) links. The result is a system that is far more 
accurate and capable than anything that existed a generation ago, 
but also one that exposes a much larger attack surface. 
Aviation relies on GNSS for instrument approaches in low 
visibility; container ships use it to navigate busy straits without 
grounding; ambulances depend on it to reach emergencies faster; 
and the emerging class of autonomous vehicles needs it, along with 
onboard sensor data, to make safety-critical decisions at highway 
speed. The stakes of getting the security wrong are therefore very 
high not just financially, but in terms of human safety.
