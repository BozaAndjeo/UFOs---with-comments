# UFOs---with-comments

Certain arguments that should have been part of SpaceShip class are all tracked separately.
Should create the class and make all the ships into objects.

Animation is currently handled by recuring Threads utilizing do-while loop,
but it should be handled by a Timer object.

On that note, ALL animation could be handled by a single recuring thread.

Laser has TWO sepperate classed objects animating itself and the explosion at it's target.
This could be handled by only one, and hopefuly together with all other animations.

StopWatch class is redundant as it's function can be better handled by System.currentTimeMillis();

tbc = to be commented on
