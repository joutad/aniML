# aniML

taikai post: https://taikai.network/hackbox/hackathons/hawkhacks/projects/clwd7m3bz0dl7z901dj51ngal/idea

### Inspiration

I was thinking to myself about all the possible applications of machine learning, and I wasn't really getting anywhere, as most ideas were already commonly being researched or developed. I then refined my focus to things that I was already interested in, and one of those things that interested me was the medium of animation, as I was in awe of the dedication put into each frame of some of my favourite animated shows.



### What it Does

aniML is a project that aims to make animation less difficult or tedious. How it works is that the user is required to draw their own beginning and ending frames (these frames are images), insert these two images into the program, and voila! The ML model will generate the intermediate frames/images for you, which will save you lots of time and effort! Animators can make use of this to quickly do some basic, rather predictable movements, while Game developers can quickly set up sprite animations, which gives them the freedom to use custom sprites without wasting an enormous amount of time on them. The project involves training a GAN to generate realistic images. Specifically, we focus on generating DRAWN images. The trained GAN takes random noise as input and learns to generate images that resemble the training data.



### How We Built It

I'm pretty much only using a python notebook and libraries like TensorFlow, NumPy, Matplotlib, and Keras for work related to building, training, and validating the discriminator, and generator (from scratch) as well as saving the model. I'm using Pillow for handling the images. I designed and implemented the architecture of the GAN, consisting of a generator and a discriminator neural network. The generator generates fake images, while the discriminator distinguishes between real and fake images.



### Challenges We Ran Into

Issues with TensorFlow shapes, directories structuring, small dataset, no tailored online references/resources, fine-tuning the model, and my lack of experience with Google Colab. I'm basically in uncharted territory.



### Accomplishments That We're Proud Of

Although not optimal, I was able to bring this idea to fruition, and this is just the first step. I've done some research and it appears that there isn't much research on creative image interpolation. Most similar works deal with real-life objects and frame smoothing, so my idea is definitely novel.



### What We Learned

Throughout the project, I gained some valuable insights into how GANs work and learned new deep learning techniques for image generation. 



### What's Next?

I want to get a better grasp of machine learning especially when it comes to training and validating, deploying, and any other steps in that process. Once I'm more familiar with this field, I do believe I can show the true potential of what I attempted to build this weekend.

