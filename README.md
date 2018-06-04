# Engine-to-Engine Tag Exchange (E2E)

The Engine-to-Engine Tag Exchange (E2E) module is meant to simplify the exchange of tags between seperate DCAF engines. Rather than configuring output and input channels manually using a specific I/O Module to exchange tags, the E2E module handles channel configuration automatically when a tag is selected to be shared between engines. The editor node of the E2E module also allows the user to determine the transfer mechanism for tag exchange. The transfer mechanism determines the allowable data types, the pairing depth (inner-target, inter-target, both), and other specific configuration information. The module was designed to allow for users to create and add new transfer mechanisms. The first two implemented mechanisms were UDP and Single Element RT FIFOs. 
