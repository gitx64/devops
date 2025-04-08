# OSI MODEL

## Layer 1: Application layer
its implemented in software or application . user commiunicates sends messages sends requests . 
 |
 |
 |   user sent message
 |
V
## Layer 2: Presentation layer
takes the data from layer1 and converts the data (char , letter , ascii) to machine level code.
|
|
|
|
v
## Layer 3: Session Layer
Helps in setting up the connections and helps authentication (sending recieving requests etc.) assumes layers below will do its things.
|
|
|
|
v
## Layer 4: Transport layer
data got from session layer will be divided into small parts like segments. And every segment will contain the port number and sequence number. flowcontrol. Also manages lost data packets by udp (doesnt require acknowledgement of recieved data).

|
|
|
|
|
v
## Layer 5: Network layer
After getting from Transport layer basically it manages the logical addressing like ip addressing. And makes ip packet with the ip address from sender and the ip of reciever to every segments of data packets. To ensure every data packet goes to the correct location. Also router resides here in this layer.
|
|
|
|
|
v
## Layer 6: Data link
It allows to directly commiunicate with computer or hosts. In that case with data packets the sender and the reciever ip address with a subnet mask will be shared with data packets. And the MAC addresses of machines are connected to the data packets.
|
|
|
|
|
v

## Layer 7: Physical Layer
The hardware section with like cables wires. Now this layer helps to convert data packets to electrical signal or if optical fibre wire then to light signals, and operates the last things.


