. display in 68x24

.. transition:: dissolve
   :duration: 0.4

QA Onboarding
=============
.. hidetitle::

QA Onboarding - Vancouver, May 22nd 2018

This presentation
=================

* https://github.com/ghanshyammann/qa-onboarding-vancouver
* presentty

About us
========

* Ghanshyam Mann (IRC: gmann)
* Masayuki Igawa (IRC: masayukig)
* Matthew Treinish (IRC: mtreinish)
* Felipe Monteiro (IRC: felipemonteiro)

Outlines:
=========
* Brief introduction to OpenStack QA
* Scope of QA Projects and team
* What we are/will be working in Rocky and beyond
* How to Contribute in QA

Brief introduction to OpenStack QA
===================================

* Official Mission Statement-

.. code::

 Develop, maintain, and initiate tools and plans to ensure the upstream
 stability and quality of OpenStack, and its release readiness at any
 point during the release cycle.


* https://wiki.openstack.org/wiki/QA

Scope of QA Projects and team
============================

* Each project team owns their QA
* Serve the OpenStack community
* Drive testing best practices
* Maintain test tools and frameworks
* Keep the gate running smoothly
* Support interoperability testing efforts
* Cross Community collaboration on testing tools etc
* Open for new testing ideas/projects

Dev & Test environment
======================

* Devstack
* Devstack-tools (python)
* Devstack plugin interface
* devstack-plugin-ceph
* devstack-plugin-container

Test Frameworks
===============

* Tempest integration testing
* Tempest plugin interface
* Tempest CLI testing
* Grenade upgrade testing
* Grenade plugin interface
* Patrole policy testing

Syntax Checks
=============

* Hacking
* eslint-config-openstack
* bashate

Test runners
============

* stestr
* os-testr

Test results
============

* openstack-health
* stackviz
* coverage2sql

What we are/will be working in Rocky and beyond
===============================================

* https://github.com/ghanshyammann/qa-updates-vancouver

Current ongoing activities
-------------------------

* https://etherpad.openstack.org/p/qa-rocky-ptg-rocky-priority
* Cross community calloboration
* OpenStack Extreme testing - https://review.openstack.org/#/c/443504/
* Misc (gate stability, plugins help)

Activities need volunteer
-------------------------

* https://etherpad.openstack.org/p/qa-rocky-ptg-rocky-priority

How to Contribute in QA
=======================

* Developer workflow

  * https://docs.openstack.org/upstream-training/upstream-training-content.html

* Fix a bug

  * Use QA tools, and then you can find documents or some other issues

* Rocky Cycle Items:

  * https://etherpad.openstack.org/p/qa-rocky-ptg-rocky-priority

* IRC  

Contacts
========

* openstack-dev ML, tag [QA] in subject
* #openstack-qa in IRC, office hours
