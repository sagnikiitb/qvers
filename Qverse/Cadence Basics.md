1.  Strongly typed language
2. REsorce are literally exit only one cope and exactly one in memory and thi i what give a piece of code money value and only ACCESS i granted to owner of object and Thoe who have valid reference to it
What are the permisssions others have who have referebce valid?

So Cadence has 3 main features :
1. Resources -> are like struct data or objects but CAN ONLY HAVE ONE COPY EVER IN THE ENTIRE BLOCKCHAIN ... So it cannot go out of scope ever in a function it needs to be stored somewhere explicitly or destroyed
2. Resources can only be EDITED by the Owner wallet unless he decides to move (give) it to someone else
3. All these 'Decisions' they cannot be performed on computer level by lay user so
4. Transactions -> Pieces of code that user approves and signs. Can be signed by multiple users and veto all that with defined weights. All this complexity can also be done by backend code so user might not 'do' anything per say just click 'Yes' and 'OK' but good for UI
5. Contracts -> Public code (though can be made private). Think of it like Class in java, it creates blueprint for all the resources to exist , user can then create resource, delete them etc using them. The whole onus is on user to run the code from the public blockchain unlike transaction which is more like a 'request' code from one user sent to other
6. Capabilities : If allowed through a signed transaction grants user B read only access to some resource fields of user A

