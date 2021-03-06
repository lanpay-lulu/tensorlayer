:mod:`tensorlayer.activation`
==============================

To make TensorLayer simple, we minimize the number of activation functions as much as
we can. So we encourage you to use TensorFlow's function. TensorFlow provides
``tf.nn.relu``, ``tf.nn.relu6``, ``tf.nn.elu``, ``tf.nn.softplus``,
``tf.nn.softsign`` and so on, see `TensorFlow API <https://www.tensorflow.org/versions/master/api_docs/index.html>`_.


.. automodule:: tensorlayer.activation

.. autosummary::

   identity
   ramp

More TensorFlow official activation functions can be found
`here <https://www.tensorflow.org/versions/master/api_docs/python/nn.html#activation-functions>`_.

Activation functions
---------------------

.. autofunction:: identity
.. autofunction:: ramp
