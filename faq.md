# Frequently Asked Questions?

1. Whats the PiFrost Project?

The PiFrost Project provides a reference implementation for architects to use to build proof of concept hybrid cloud networks leveraging AWS Transit gateway.

2. Is there a cost associated for implementing this project?

The cost for implementing this project is about $10/month. This includes the VPN connection and the EC2 instance used to test. The utilization of the connection will effect the cost.

3. Is there a recommendation on Raspberry Pi model?
The model used to create this project was a Raspberry Pi 3, Model B.

[Here is a link to purchase](https://www.amazon.com/Adafruit-PiTFT-2-2-HAT-Mini/dp/B00S7GAVEO/ref=sr_1_15?keywords=adafruit+raspberry+pi+3&qid=1553791842&s=gateway&sr=8-15)

4. Do we have a cloudformation template for the building out the AWS environment?
There isn't currently a CloudFormation template.

5. What version of Openswan are we using? Can I use another VPN software?

We're using Openswan version 2.6.38. We recommend using the latest version available. Other open source VPN software can be used, but you will need to reference their implementation instructions.
