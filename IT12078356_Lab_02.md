###IT12078356##
### U.P.P.Nilanga##

# Creating an Amazon EBS-Backed Linux AMI #
------------------------------------------
## To create an AMI from a snapshot using the console ##

###1. Open the Amazon EC2 console. ###

![](https://scontent-ams3-1.xx.fbcdn.net/hphotos-xta1/v/t1.0-9/11800386_10206499543463147_849852527531137827_n.jpg?oh=2702a96ae1aeafd613036c9f49fcb3de&oe=56483EE4)

###2. Connect to the instance and customize it. ###
![](https://scontent-ams3-1.xx.fbcdn.net/hphotos-xft1/v/t1.0-9/10407721_10206499544463172_3782987514211597234_n.jpg?oh=acc6294bddc72cc8e2ddcb471e6a7e2d&oe=564D474C)

![](https://scontent-ams3-1.xx.fbcdn.net/hphotos-xtf1/v/t1.0-9/11800031_10206499545583200_8410424763401079802_n.jpg?oh=baabc45e77f187138b7512cf3be81a77&oe=5653E400)

![](https://scontent-ams3-1.xx.fbcdn.net/hphotos-xfp1/v/t1.0-9/11060272_10206499545983210_1227359042237096851_n.jpg?oh=b280da595bd358e69c854479983399c1&oe=560E7A03)

### 3. In the navigation pane, click Instances and select your instance. Click Actions, select Image, and then click Create Image. ###
![](https://scontent-ams3-1.xx.fbcdn.net/hphotos-xta1/v/t1.0-9/11143337_10206499544743179_1270351143134152151_n.jpg?oh=13eb2601f8fe5cf18081fa12098a1a8a&oe=56579D57)

### 4. In the Create Image dialog box, specify the following, and then click Create Image. ###

1. A unique name for the image.
2. A description of the image, up to 255 characters.
3. By default, Amazon EC2 shuts down the instance, takes snapshots of any attached volumes, creates and registers the AMI, and then reboots the instance. Select No reboot if you don't want your instance to be shut down.
4. 
![](https://scontent-ams3-1.xx.fbcdn.net/hphotos-xat1/v/t1.0-9/11800377_10206499546223216_3223160959371403394_n.jpg?oh=bdab4fbbf4e3be8e78e3fd01adaef714&oe=5610B7AD)

![](https://scontent-ams3-1.xx.fbcdn.net/hphotos-xpf1/v/t1.0-9/11742801_10206499546423221_5464076821288362894_n.jpg?oh=75895ecb13604fd4666875491d71122d&oe=5642DE1A)

### 5. Click AMIs in the navigation pane to view the status of your AMI. While the new AMI is being created, its status is pending. This process typically takes a few minutes	to finish, and then the status of your AMI is available. ###
![](https://scontent-ams3-1.xx.fbcdn.net/hphotos-xpt1/v/t1.0-9/11702899_10206499546903233_3941934732418470420_n.jpg?oh=a1f6d43645a60af1833b66a107e054f9&oe=565B8113)

## Creating a Linux AMI from a Snapshot ##

###1. In the navigation pane, under Elastic Block Store, choose Snapshots. ###
![](https://scontent-ams3-1.xx.fbcdn.net/hphotos-xpt1/v/t1.0-9/11702705_10206499547183240_8393089518312651784_n.jpg?oh=77884ac4183db4e8ad73d2ab98d9424d&oe=56552390)

### 2. Choose the snapshot, and then choose Create Image from the Actions list. ###

![](https://scontent-ams3-1.xx.fbcdn.net/hphotos-xpt1/v/t1.0-9/11202586_10206499547383245_8463364222172112944_n.jpg?oh=636bf4de8da6686405ce98e2f8053e6c&oe=56579C4E)

![](https://scontent-ams3-1.xx.fbcdn.net/hphotos-xpa1/v/t1.0-9/11760059_10206499547503248_7260171329345935914_n.jpg?oh=3bf3ad2c1f5539b7a2410a0296414d59&oe=56170BC6)