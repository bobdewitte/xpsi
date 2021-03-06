.. module:: xpsi.Pulse

.. _pulse:

Pulse
=====

Instances of :class:`~.Pulse.Pulse` are objects which define the
generative relationship between the pulse and X-ray photon data.
That is, the parametrised sampling distribution of the photon data is defined.

.. autoclass:: xpsi.Pulse.Pulse
    :members: __call__, _construct_energy_array, energies, fold, loglikelihood
    :show-inheritance:

.. autoclass:: xpsi.Pulse.LikelihoodError
    :show-inheritance:
