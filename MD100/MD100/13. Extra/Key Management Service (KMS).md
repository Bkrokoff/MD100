# KEY MANAGEMENT SERVICE (KMS)

- An activation service that allows organizations to activate systems within their own network, eliminating the need for individual computers to connect to Microsoft for product activation.

You can use this tool to activate the computers without connecting the network to the internet. 

You can configure one of the computers as a Key Management Service (KMS) host and activate the KMS host by phone. The other computers in the isolated network can then activate using the KMS host.

Installing a KMS host key on a computer running Windows 10 allows you to activate other computers running Windows 10 against this KMS host and earlier versions of the client operating system, such as Windows 8.1 or Windows 7.

Clients locate the KMS server by using resource records in DNS, so some configuration of DNS may be required.

[[Volume Action Management Tool (VAMT)#^16687d|VAMT]] is the tool used to run KMS