.. figure:: img/gsoc/gsoc_logo_main.png
   :alt: Google Summer of Code logo
   :align: center

\

\

.. _intro:

============
Introduction
============

The Global Wireless Mesh Network market is expected to grow from USD 3,45 Billion in 2017 to USD 12,1
Billion in 2026 [#f1]_, at a Compound Annual Growth Rate (CGAR) of 15%, as a response to the growing
adoption of connected devices in industry, army and civil applications.

WMNs use directional and omni-directional antennas. The first ones are capable of reaching very far
distances, and are the-best fit solution for networks that serve vast environments; however, since directional
antennas can’t change their pointing direction, the topology results to be static and stiff, and a local failure
can have repercussions at the macro level.

When the network needs to change dynamically, (e.g. in case of upgrades, problem-fixings, optimizations)
directional antennas have to be rotated either manually or with an automated system. The solution provided
by this work is a light, low power consuming self-rotating remotely controlled system, called Turnantenna.

The design process of the Turnantenna follows a practical approach: theoretical solutions that comes from
physical analysis are systematically tested in practice with the realization of a prototype. The Turnantenna
is primarily thought to be used by Wireless Community Networks users, whom are inexperienced people.
The simplicity of assembly is pursued to give those people the possibility to build the Turnantenna
themselves, in order to help networks’ growth. The design process is held in close contact with those
communities, in particular Ninux, and people whom have a great experience in the field.

The directional antenna is equipped with two stepper motors that allows the rotation around two distinct
axis. When the wind blows at the maximum design speed of 37,5 m/s, the entire system consumption is
24W, which is reduced when wind blows in ordinary conditions (<8m/s) and engines could be switch off.

In conclusion, the Turnantenna is a cheap, effective solution for directional antenna problems in WMNs.
Industry 4.0 is based on a strong and stable wireless coverage, and the benefits of this system can have a
considerable impact on the overall performances for networks that serves big areas.

-------------------------------------------------

.. [#f1] `Research and markets <https://www.researchandmarkets.com/reports/4562504/wireless-mesh-network-global-market-outlook>`_