# LoRa-packet-delivery-with-acknowledgement
This LoRa project includes a client which will retransmit metrics if the receiver does not acknowledge the receipt. 

This video https://youtu.be/X8Ghand1gbE explains how I setup a Maduino client to transmit to a server and expect an acknoledgement else, it will retransmit up to 3 attempts at random intervals. I tried several of the Reyax modules with a Nano and found them to be unreliable. The Maduino is rock solid for me but, lacked the addressing which I found a way to work around.  

Future additions to this code could include fault tolerance (multiple servers). Round trip time of communications could also be added which would aid in duty time awareness. Since only a source address needs to be entered, a detachable keyboard and LCD might be a good idea as this would lessen the need for a laptop in the field.

I wrote this code for a project involving a campus environment where hundreds of pedestals would be transmitting data every 5-10 minutes back to a server. 

I am a novice software programmer.  Check this code carefully. I hope it helps you.
