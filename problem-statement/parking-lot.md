#Designing a Parking Lot System

##Requirements:

1.Vehicle will come at entry 

2.There would be multiple entry and exit

3.ParkingLot will have have multiple floors.

4.Vehicle can be car \/bike \/truck 

5.There would be sperate spot for each parking vechicle 

6.System will find the parking spot for the vechcle 

7.At time of exit ,user can pay the payment 

8.Parking spot will become empty after the exit 

##Additional Info:
1. we can notify user after the exit and use observer pattern for sending notifications

2. We should have single parking lot class and can use singleton pattern 

3. we can have multiple parking strategy for the spot identification and payment strategy for cas/ card payment 

##UML Class Diagram 

![](../class-diagrams/parking-lot-class-diagram.jpeg)

##Implementation
![Java Implementation](../solutions/java/src/parking-lot-system/)
