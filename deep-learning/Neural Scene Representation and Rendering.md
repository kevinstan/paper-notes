# Summary:
In this paper, Eslami et al. (DeepMind) demonstrate that generative models are capable of learning compact latent representations of the properties of physical objects for the purpose of "imag- ining" physical properties even when faced with object occlusion (e.g. if you can only see 3 legs of a table, you can imagine where the 4th should be). They propose the Generative Query Network (GQN) that trains only on data observed by itself, consisting of two parts: a representation network and a generation network. They demonstrate the ability for an agent to explore the learned 3D environment through "neu- ral rendering".

# Takeaway:
The GQN can "imagine" previously unseen scenes from a new query camera viewpoint. However, they use a synthetically generated environment of primitive geometrical objects. Future works should attempt to achieve similar results in high-resolution, real-world environments.
