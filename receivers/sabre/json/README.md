# Sabre Receiver Templates

This directory contains sample templates for interacting with the Sabre GDS through spreedly. A template for performing a round trip flight booking and a template for performing a hotel booking are provided. In both cases, the data that is "templated" is the data that needs to be filled in for Spreedly to fill in before forwarding to Sabre.

For both the hotel booking and the flight booking there are two files provided. One that includes a readable version of the templated body that will be sent to Spreedly and then forwarded. The other file is the exact payload that will be sent to Spreedly including the payment method id to use. This includes the body from the previous file but is less readable since the json body that will be sent along is encoded as a string.
