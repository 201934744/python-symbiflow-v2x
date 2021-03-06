Manually set output as clock by setting the CLOCK attribute
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

The following shows that ``output wire o`` is given the ``(* CLOCK *)`` attribute.

.. symbolator:: ../../../tests/clocks/output_attr_clock/output_attr_clock.sim.v

|

.. no-license:: ../../../tests/clocks/output_attr_clock/output_attr_clock.sim.v
   :language: verilog
   :caption: tests/clocks/output_attr_clock/output_attr_clock.sim.v

As such, the ``is_clock`` attribute of the ``o`` port is set to 1.

.. literalinclude:: ../../../tests/clocks/output_attr_clock/golden.model.xml
   :language: xml
   :caption: tests/clocks/output_attr_clock/golden.model.xml