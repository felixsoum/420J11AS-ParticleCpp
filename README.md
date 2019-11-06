# 420J11AS-ParticleCpp

## Make a trap BP
1. Make Trap C++ class
1. Add a Box Component
1. Compile and create a BP from it
1. Override NotifyActorBeginOverlap
1. Add debug message when overlapping
1. Put it in the level and test

## Create a simple explosion
1. Create a material
1. Create a particle system
1. Add the particle system field to ATrap
1. Use UGameplayStatics to spawn the emitter

## Launch player in the air
1. Declare a FVector for the impulse
1. Add the impulse to the player's character movement component
