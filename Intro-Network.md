Layer 7, the Application layer, helps programs on a computer communicate with each other by providing a way to transmit data. When data is given to this
layer, it's passed down to the Presentation layer.

Layer 6, the Presentation layer, receives data from the Application layer and makes sure it's in a format that can be understood by the receiving computer.
It also handles encryption, compression, and other transformations to the data, before passing it down to the Session layer.

Layer 5, the Session layer, tries to set up a connection with the other computer across the network. If it can establish a session, it's responsible for
maintaining it and making sure the communication is synchronized. This layer allows multiple requests to be made simultaneously without data getting mixed up. Once a connection is established, data is passed down to Layer 4: the Transport layer.

Layer 4, the Transport layer, chooses the protocol to use for transmitting data, such as TCP or UDP. It also divides the transmission into smaller pieces
and ensures that they are sent to the correct place.

Layer 3, the Network layer, locates the destination of the request using logical addressing, such as IP addresses. It figures out the best route to take to 
reach the destination.

Layer 2, the Data Link layer, adds the physical address of the receiving endpoint, known as the MAC address, to the transmission. It also checks for any errors
in the received data.

Layer 1, the Physical layer, is where the actual electrical pulses that make up the data transfer happen. It converts binary data into signals and transmits
them over the network, as well as receiving incoming signals and converting them back into binary data.
