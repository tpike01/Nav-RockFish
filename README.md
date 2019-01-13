# Nav
Navigation - in order to travel in time and space you need your current location and the destination.

Your current location is a 3D co-oridnate [x,y,z], and your destination is another 3D co-ordinate [x', y',z'].

       #------------------------------------------------#
    [x,y,z]                                          [x',y',z']

How you travel from current location to destination depends on many factors. ie gravity, obsticles, wind, having the resources to get to the destination, this may be fuel ie gas if its a car, battery if its an electric vehicle, enough food & water to survive the journey if its on foot for instance. There is little point in attempting a journey unless there is a good chance of success. You need the resources to get to your destination, so its always good to calculate this before embarking on a journey. There may be ways to top up your resources on the way ie solar panels ( so you need sun for that, so your rover may get 50% of the way then it gets dark, the rover falls asleep because the solar power is depleted and then in the morning the sun comes up and the solar panels start storing power again, and the journey continues ).

So lets take a simple case, Point A to Point B with nothing in between, the most obvious path is a straight line, however this may depend on the terrain, for instance a stright line may be up a steep hill and this may not allow our rover to climb up this hill, because it just doesn't have the power to get up the steep hill, where as if it takes a meandering path that is less steep and the rover is able to follow this path with its limited power, then it will get there, but it won't be by taking a straight path but by taking the optimal path given the resources.

So navigation at first glance is pretty straight forward, but it isn't at all, its complicated.

Here is one more example, the Chinese landed a space craft on the dark side of the moon today (Thursday 03 Jan 2019). You might think thats not so cool considering the US landed men on the moon almost 50 years earlier (July 20, 1969), but then you need to think about what the Chinese had to do in order to communicate with their space craft on the dark side of the moon. If they had a fully autonomous craft they could have landed it but nobody on earth would know that it was there and nobody would be able to see the pictures it took or get any of the realtime telemetry data from the craft, experimental data etc, because its on the dark side of the moon where there is no way to send and recieve radio signals, unless you can bounce the signals off another space craft we call a satelite. So first the Chinese had to send up a satelite to park in geo stationary orbit over the dark side of the moon in just such a location that signals could be sent and received from earth to the satelite and then back and forth to the space craft on the dark side of the moon. So just to get communications you need a rocket to launch the satelite, then you need another rocket to launch the spacecraft thats going to land on the darkside of the moon. The communications need to work really well in order for the mission to succeed. Then you need to fly the spacecarft to the darkside and land it in its designated destination point on the dark side of the moon. Navigation is difficult, and the Chinese just showed us how difficult it can be to achieve great navigation. Sometimes a journey takes years of planning.

Mankind will always be navigating further and further... happy trails...




