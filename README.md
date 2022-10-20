# Neural-Decoding
Neural decoding uses activity recorded from the brain to make predictions about variables in the
outside world or put simply put, it is a mathematical mapping from the brain activity to the
outside world. For example, we may predict movements based on activity in the motor cortex,
decisions based on activity in prefrontal and parietal cortices, and spatial locations based on
activity in hippocampus. As deep learning methods have become more popular over the last
decade people have experimented with them to test how effective they are as neural decoders.<br>
The motivation behind this paper is that improving the performance of neural decoding
algorithms allow neuroscientists to better understand information contained in a neural
population and can help advance brain machine interfaces and thus it is very important to
discuss what these neural decoders do and what their limitations are. <br>
In this project I compare three different methods for neural decoding and present several graphs
to compare their performance. The sample dataset I will be working on will come from this
paper (example_data_hc.pickle) which is recordings animal hippocampus. They have published
their code opensource on github (https://github.com/KordingLab/Neural_Decoding). I did not
change some of the functionalities like data preprocessing step and the scoring functions. I
have used hippocampus data purposefully because I expect there to a non-linear relationship
between the input and the output. Hippocampus has a major role in learning and memory. In the
last part of the project I discuss the effectiveness of deap learning models in neural decoding
and the limitations of decoders in general.
