Event Preprocessing Tutorial:

Stream of events is easy to be analyzed directly, but difficult to be used in modern deep learning models, which use tensors to accelerate the training. In order to benefit from the existing deep learning ecosystem, as well as to take full advantage of GPUs and other hardware accelerators, we encode our raw events into tensors.

In this tutorial, you will learn about different preprocessing methods to extract key information out of the raw events, and to convert them to a dense representation that can be used in deep learning.

Before we begin, let’s first have a look at the tensor representation.
