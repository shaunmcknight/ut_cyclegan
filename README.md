# UT cyclegan
A image-to-image generative model which introduces task specific modifications to CycleGAN, to learn the mapping from physics-based simulations of defect indications to experimental indications in resulting ultrasound images. The resulting synthetic dataset resulted in an improved F1 classification score on experimental ultrasonic images of 0.45 (from 0.394 to 0.843), when training a CNN classifier on simulated and GAN generated data.


Example simulated defect:

![image](https://user-images.githubusercontent.com/71640417/223427399-f2470a2e-a70b-4074-8b8e-963c278bccfb.png)


Example experimental response:

![image](https://user-images.githubusercontent.com/71640417/223427454-39b883a9-fa3c-454f-b102-016a923d0b37.png)


Introduction of a mid activation map loss to encourage accurate defect reconstruction.

![image](https://user-images.githubusercontent.com/71640417/223427211-148c4e1f-77ac-457b-9bdf-5d113823c19f.png)


Example of GAN generated responses and comparative experimental:

![image](https://user-images.githubusercontent.com/71640417/223427551-666e0ead-39f1-439b-8279-45f022c668d6.png)
