468	10:19:56 PM 9/28/2021	32.9689282	W10C1 	RRAS  	IKE	IKE:version 2.0, IKE_AUTH, Payloads = HDR, Flags = Initiator , Length = 2508	{IKE:6, UDP:23, IPv4:22}
469	10:19:56 PM 9/28/2021	32.9689282	W10C1 	RRAS  	IPv4	IPv4:[Fragment, Offset = 976] Src = 192.168.2.105, Dest = 192.168.3.101, Next Protocol = UDP, Packet ID = 62072, Total IP Length = 996	{IPv4:22}
470	10:19:56 PM 9/28/2021	32.9689282	W10C1 	RRAS  	IPv4	IPv4:[Fragment, Offset = 1952] Src = 192.168.2.105, Dest = 192.168.3.101, Next Protocol = UDP, Packet ID = 62072, Total IP Length = 588	{IPv4:22}

Server client

494	10:19:56 PM 9/28/2021	33.0109413	RRAS  	W10C1 	IKE	IKE:version 2.0, IKE_AUTH, Payloads = HDR, Flags = Responder , Length = 1996	{IKE:6, UDP:23, IPv4:22}
495	10:19:56 PM 9/28/2021	33.0109413	RRAS  	W10C1 	IPv4	IPv4:[Fragment, Offset = 1480] Src = 192.168.3.101, Dest = 192.168.2.105, Next Protocol = UDP, Packet ID = 27191, Total IP Length = 548	{IPv4:22}



EnableServerFragmentation

![[Pasted image 20210930084957.png]]

![[Pasted image 20210930085627.png]]

With IKEv2 fragment.

![[Pasted image 20210930094439.png]]

With out IKEv2 fragment.
![[Pasted image 20210930094709.png]]

![](https://i0.wp.com/atoughnut.com/wp-content/uploads/2020/08/Backlink1.png?resize=506%2C259&ssl=1)
