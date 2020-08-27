# Exchangable Id

This project started as a poc for contact tracing which was developed using Hyperledger and Flutter.

Exchangable Id can used for corona tracing in a privacy preserving way. A Specialised node request chain for a an Exchangable Id which is generated using randomness-collective-flip and recorded to the state. Using offchain workers the data is stored privately and keys are rotated among the users. 

When two mobile having Exchangable Id activated comes in proximity both the mobile trigger an on function to record the contact. If any of the users turn out covid positive he can invoke on chain function to notify his contact.