# aci-golf
<P>
<B>UPDATE OCT 2017</B>
<P>
<I>The response to my ACI videos and this repo has grown beyond my intial expectations and I am truly flattered.  That is good news for ACI but it brings a problem too.  The configs you see here are examples only.  What is germaine to my own lab and config style might not exactly match your environment.  My only sincere request is not to take what you find here verbatim, but use it, and review the configs in the context of your own setup and make appropiate decisons to adapt it for what works for you.  Ask questions!  Does this config make sense for me?  Should I use a different mask, etc etc.
</I>
<HR>
<P>
This repo contains the sample running configurations of ACI GOLF Routers, which are peering with the fabric spines across an existing multipod setup.  I also include an optional configuration for an MPLS-PE router, which is not integrated with ACI but used to simulate a greater WAN network and test routing and connectivity towards ACI via the GOLF routers.  
<p>
All example routers are based on the Cisco CSR1Kv virtual router, which is not supported in GOLF production environments, but is suitable for design and lab testing.  I am using the freely downloadable demo version, which is limited in capability, but still able to run GOLF.
<p>
Please review the topology I have below.  Note that this does not represent a true production setup as my lab is lacking redundancy at many levels, including spines, IPN devices and GOLF routers.  <B>This is an example only to help you get started with your own testing</B>.  In your real world, you would refer to any official Cisco design guide and account for failure domains and redundancy as appropriate.  This is not that.
<p>
<I>Shout out to Max Ardica and Soumitra Mukherji (both Cisco).  All of my examples are based on their original work on the topic.</I>
<p>
<a href="https://github.com/joezersk/aci-golf/blob/master/Running-Config-GOLF-WEST">Repo link to running-config of GOLF-WEST Day-0 configuration</a>
<p>
<a href="https://github.com/joezersk/aci-golf/blob/master/Running-Config-GOLF-EAST">Repo link to running-config of GOLF-EAST Day-0 configuration</a>
<p>
<a href="https://github.com/joezersk/aci-golf/blob/master/running-config-MPLS-PE">Repo link to running-config of MPLS-PE</a>
<p>
<hr>
<p>
<img src="https://github.com/joezersk/aci-golf/blob/master/ACI-GOLF-Sample-Topo3.png">
