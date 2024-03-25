• I have implemented and simulated an Internet network in Cisco packet tracer Student.

• I have used the Router – PT, because it has all the necessary ports pre – installed, so it is much more convenient to use.

• For switches, I have used the generic 2950 – 24 switch, which has 24 ports.

• For end devices, I have used generic laptops for the same.

• For connection between an end device and a switch, I have used the Copper – Straight through cable.

• For connection between a router and a switch, I have used a Copper – Straight through cable.

• For connections between 2 routers, I have used either Optic Fiber or Serial DCE cable.

o Note that I have prioritized using the Optic fiber cable rather than the Serial DCE cable.

o I have done this in such a way because the Optic fiber is much more faster than the Serial cable in terms of transferring data.

• The steps I followed:

1.  Setting up a laptop and the corresponding router:+
   
        a. Set the IP of the laptop IP to the desired IP
        b. Make sure to set the corresponding router port’s IP is on the same network as that of the laptop
        c. Set the “Default gateway” of the laptop to the IP of the connected router
    
3.  Setting up 2 routers:
   
        a. Make sure that when connecting 2 router’s their corresponding port’s Ips are on the same network
    
5.  Router:
   
        a. Make sure to add the Network address of all the existing networks ofn the router to the RIP table
    
7.  For example
   
        a. Connection between a router and a laptop
            i. If the IP of the laptop is “192.168.1.1”
            ii. The IP of the corresponding router can be anywhere on the same network, “192.168.1.2”
            iii. These IPs cannot be same
            iv. The default gateway of the laptop now must be set to the IP of the corresponding router, in this case “192.168.1.2”
            v. The network address “192.168.1.0” must be added to the RIP table of the router.
            vi. None of the assigned IPs can be a network address.
        b. Connection between 2 routers:
            i. The IPs of 2 connected routers must be in the same network as well.
            ii. If the IP of the first router is “192.168.2.1” then, the IP of the second router can be “192.168.2.2”
            iii. The network address of these IPs must be added to the RIP table of both the routers.

![image](https://github.com/SkeyPr/Routing_Example/assets/118352620/b0a10541-d948-44d4-94c5-3f1417982812)

P.S. After downloading the file, wait for 4-5 minutes for all the routers to boot up. The first few data transmissions will be unsuccessful, however the latter ones will be successful.
