### What kind of information do you retrieve by pinging an IP address from a single VP?

We get a Reachability, Round-Trip Time (RTT), Packet Loss, TTL (Time to Live) IP Address Resolution or Error Messages

### Describe how we can extract a geographical distance from a ping between a VP and an IP address

By using the RTT from the ping and 2/3 of the speed of light, we can calculate a perimeter around the vantage point where the target IP adress might be.

### You made your measurements and issued a ping toward the target from a set of VPs. Which one is giving you the most precise estimation of the target’s geolocation?

The one with the shortest RTT

None, we use ALL the perimeters of our VP to get some common area between all perimeters.
We can then estimate a more accurate area where the target might be by using that shared area from all the VP and their perimeters.

### Can you think about a way to use multiple distance information to estimate the geolocation of the IP address? (Hints: think about how GPS work)

Triangulation