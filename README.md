## NGLite
* Anonymous cross-platform remote control program based on blockchain network
* Implementation principle: [link](https://maka8ka.github.io/post/一个基于区块链网络的匿名远控/)

## Advantages & Disadvantages

Theoretically complete anonymity, except of course if someone monitors and analyzes all the intermediate nodes, currently there are about 8W nodes.

No need for any public network resources, just need the communication host to be able to access the internet.

No need to buy IP/Domain/Server/CDN resources with real name.

Currently, the performance of no-kill is excellent

A little more connections, the volume is larger, you can compress it by yourself through the upx and so on.

## Currently supported parameters

```powershell
Console
-n new Generate new channel/group/seed
-g 9e8124591f55d27b48ba907f2ad39e790ec589b3942dec2a19e7c2a96b751922 specify 9e8124591f55d27b48ba907f2ad39e790ec589b3942dec2a19e7c2a96b751922 channel
$mac$ip shell Send shell command to executing host

Controlled end
-g 9e8124591f55d27b48ba907f2ad39e790ec589b3942dec2a19e7c2a96b751922 Designation 9e8124591f55d27b48ba907f2ad39e790ec589b3942dec2a19e7c2a96b751922 channel
``

## Example
! [example](https://raw.githubusercontent.com/Maka8ka/NGLite/main/example.png)

## Subsequent development

Due to the characteristics of P2P and the distribution of more than 7w network nodes, this network has the inherent advantages of large file transfer and network transmission speed.

We will consider adding file transfer, intranet penetration proxy and other functions.

The code is a bit messy, but we will organize it later and update the source code after separating the functions.

## Detection
! [detection](https://raw.githubusercontent.com/Maka8ka/NGLite/main/detection.png)


## Warning!!!
This remote control program is a convenient operation and maintenance tool for operation and maintenance personnel, please use it appropriately, and the user is responsible for all illegal behaviors and consequences.

## My Sapce
[Maka8ka's Garden](https://maka8ka.github.io)





Translated with DeepL.com (free version)