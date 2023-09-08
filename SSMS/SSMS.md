# SSMS
SSMS (Secure Short Message Service) is a custom protocol based off of the widely used SMS (Short Message Service) protocol used for text messaging by most telephone, internet, and mobile devices. The goal is to provide an additional layer of security to the pre-existing SMS protocol.

## How Standard SMS Works
As of now, SMS works in 5 simple steps.
* First: You send a text message.
* Second: That message gets transmitted from your device to your nearest Cell Tower.
* Third: That Tower sends the message to an SMS Center (SMSC). These Centers are provided by your Cellular Provider (Verizon, AT&T, etc.)
* Fourth: The SMSC sends your message to a cell tower near the recipient.
* Fifth: That tower sends the message to the recipient. 
