# aci-golf
<P>
This repo contains the sampe running configurations of ACI GOLF Routers, which are peering with the fabric spines across an existing multipod setup.  I also include an optional configuration for an MPLS-PE router, which is not integrated with ACI but used to simulate a greater WAN network and test routing and connectivity towards ACI via the GOLF routers.
<p>
Please review the topology I have below.  Note that this does not represent a true production setup as my lab is limited and lacking redundancy at many levels, including spines, IPN devices and GOLF routers.  This is an example only.  In your real world, you would refer to any official design guide and account for failure domains and redundancy as appropriate.  
<p>
<hr>
<p>
<img src="https://github.com/joezersk/aci-golf/blob/master/ACI-GOLF-Sample-Topo2.png">
