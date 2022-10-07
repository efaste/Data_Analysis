## How DoorDash is improving customer deliveries by using location data 
- The the past DoorDash they typically used from a Dasher's phone. These updates are triggered along the way by manual requests for Dashers to check in when they've arrived at a restaurant or picked up food, as well as [[GPS]] data from a Dasher's phone. However, we've been trying to reduce manual intervention and increase the accuracy of this location information.

![[Pasted image 20220930173833.png]]

- They just released an update to the Dasher and merchant apps that makes use of [[bluetooth]] signals (technically known as "[[Beacon]]") to notify them when a Dasher enters or exits a restaurant. Now, if a Dasher has bluetooth turned on, the bluetooth signals in the two apps will start communicating as soon as they are within 20 feet of the merchant app, alerting DoorDash that the Dasher has arrived at the restaurant. When the Dasher's communication range with the tablet is broken, a similar notice indicating that the user has left the store will be sent.


More information
- [Scaling DoorDash’s Geospatial Innovation with a Location-Based Delivery Simulator - DoorDash Engineering Blog](https://doordash.engineering/2020/08/12/scaling-geospatial-innovation-with-a-location-simulator/)
