.. _user-guides:

User guides
===========

User guides are deeper dives into particular topics within JAX
that become relevant as your JAX project matures into larger
or deployed codebases.

.. toctree::
   :maxdepth: 1
   :caption: Debugging and performance

   notebooks/thinking_in_jax
   profiling
   device_memory_profiling
   debugging/index
   gpu_performance_tips
   persistent_compilation_cache

.. toctree::
   :maxdepth: 1
   :caption: Development

   jaxpr
   notebooks/external_callbacks
   type_promotion
   pytrees

.. toctree::
   :maxdepth: 1
   :caption: Run time

   aot
   export/index
   errors
   transfer_guard

.. toctree::
   :maxdepth: 1
   :caption: Custom operations

   pallas/index
   ffi
