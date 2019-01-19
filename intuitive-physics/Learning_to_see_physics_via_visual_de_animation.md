# Summary: 

In this paper, Wu et al. offers an approach to scene understanding that is both rich and fast. They propose a framework for learning representations about physical scenes based on three parts: a perception module, a physics engine, and a graphics engine. First, the perception module is run to build the physical scene representation of a given still image. Then, the physics engine is run to make sense of the scene representation and generates what we expect to see in the future. Finally, this is visualized via the graphics engine at the raw pixel level.

# Takeaway:
Simulation engines learn an interpretable and rich model of the physical world, and crucially learns in a self-supervised manner (by computing gradients of the likelihood function to evaluate the dif- ference between synthesized scenarios and the initial observed environment).
