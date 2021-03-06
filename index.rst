.. AADL documentation master file, created by
   sphinx-quickstart on Wed Mar  7 14:26:16 2018.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

What is AADL?
=============

Developed by a `SAE International <http://www.sae.org/>`_ sponsored committee of experts, the Architecture Analysis & Design Language (AADL) was approved and published as `SAE Standard <http://standards.sae.org/as5506b/>`_ AS-5506 in November 2004. Version 2.1 of the standard was published in Sept 2012.

The AADL is designed for the specification, analysis, automated integration and code generation of real-time performance-critical (timing, safety, schedulability, fault tolerant, security, etc.) distributed computer systems. It provides a new vehicle to allow analysis of system designs (and system of systems) prior to development and supports a model-based, model-driven development approach throughout the system life cycle.

Benefits of AADL
----------------

The SAE AADL standard can lower development and maintenance costs by

.. image:: images/logo-dimensions.jpg
    :align: right

* providing a standard, precise syntax and semantics for performance-critical systems, so that documentation can be well defined
* providing the ability to model large-scale (multi-contractor) architectures from many aspects in a single analyzable model that can be incrementally refined
* capturing the “architectural API” needed to evaluate the effect of change, such as the emergent properties of integration (e.g., safety, schedulability, end-to-end latency, and security)
* allowing early and life-cycle tracking of modeling and analysis
* analyzing the system structure and runtime behavior, complementing functional simulation
* providing a great complement to reference architectures and component-based or product-line development

Actual users and AADL-related projects
--------------------------------------

As an `international industry standard <http://standards.sae.org/as5506b/>`_, AADL enjoys growing acceptance in avionics, aerospace, medical, nuclear, automotive, and robotics communities. You can find out more presentation materials and more details under the wiki section dedicated to the `standardization committee works <https://wiki.sei.cmu.edu/aadl/index.php/Standardization>`_, and all :ref:`publication materials <learning>` related to AADL.

The standardization committee has an active participation from industrial and academic partners, including Adventium Labs, Aerospace, Airbus industries, Boeing, Carnegie Mellon Software Engineering Institute, Chinese Academy of Science, Dassault Aviation, Edgewater, Ellidiss, European Space Agency, Honeywell, INRIA, ISPRAS, ISAE, IRIT, Kansas State University, NASA, Rockwell-Collins, Rolls-Royce, Russian Academy of Science, TELECOM ParisTech, Toyota, U.S Army, University of Pennsylvania. Also, the committee is in active collaboration with other standardization bodies including the `ARINC653 working group <http://www.aviation-ia.com/aeec/projects/apex/>`_, the `SAVI initiative <http://savi.avsi.aero/>`_ and `The Open Group Real-time <http://www.opengroup.org/getinvolved/forums/systems>`_. 

.. _learning:

Learning AADL
=============

Model-Based Engineering with AADL
---------------------------------

Peter Feiler and Dave Gluch authored the book Model-Based Engineering with AADL: An Introduction to the SAE Architecture Analysis & Design Language which covers the basics of the language and the related analysis tools. The book is `available for purchase online <http://www.informit.com/store/model-based-engineering-with-aadl-an-introduction-to-9780321888945>`_ under a hard cover or epub format. 

Software Engineering Institute Resources
----------------------------------------

AADL webinar
^^^^^^^^^^^^

The Software Engineering Institute `has published a webinar on Architecture Analysis with AADL <http://resources.sei.cmu.edu/library/asset-view.cfm?assetID=424907>`_. The presentations introduces the main concepts of the language and also its analysis capabilities to validate resource budgets, latency and safety.

`The webinar is available online <http://resources.sei.cmu.edu/library/asset-view.cfm?assetID=424907>`_ with all the presentation materials: video and slides. 

SEI blogpost articles
^^^^^^^^^^^^^^^^^^^^^

The Software Engineering Institute regularly publishes articles on its `official blog on AADL <http://blog.sei.cmu.edu/>`_. It provides updates and informations about what is new in the language and what is the new tools or research that use the technology.

The articles are available online on the blog under the `AADL category <http://blog.sei.cmu.edu/archives.cfm/category/architecture-analysis-design-language-aadl>`_.

SEI podcasts
^^^^^^^^^^^^

The Software Engineering Institute regularly publishes podcast about AADL. The podcasts feature people from different backgrounds, providing different perspectives about its use in industrial and academic environments.

The podcasts are available on the `SEI podcast series <https://resources.sei.cmu.edu/library/results.cfm?as_q=inmeta:AssetType~Podcast>`_ under the Software Architecture category. They are also available on the `iTunes store under the Software Engineering Institute Podcast Series <https://itunes.apple.com/us/itunes-u/software-engineering-institute/id566573552?mt=10>`_. 

Research Publications
---------------------

The AADL language and tools are used in many `industrial or academic projects <https://wiki.sei.cmu.edu/aadl/index.php/Projects_and_Initiatives>`_. The AADL wiki has a dedicated section that maintains a `list of existing publications <https://wiki.sei.cmu.edu/aadl/index.php/AADL_Related_Publications>`_ organized by topics, years, etc. 

Tutorials, Demonstrations, and Teaching
---------------------------------------

There are a few demonstrations available online. Most of them are available online and `listed on the AADL wiki <https://wiki.sei.cmu.edu/aadl/index.php/Models_examples>`_. Also, the AADL standardization meeting regularly hosts tutorials and tools demonstrations. A `list of all existing tutorials <https://wiki.sei.cmu.edu/aadl/index.php/AADL_Tutorials>`_ is available online.

The Software Engineering Institute also offers specific AADL-related courses. They can be delivered at the Software Engineering Institute or on another specific location. The course are presented by AADL experts that design the language and implement OSATE. They can answer very specific questions related to modeling and the AADL. For more information, please read the `related information on the SEI website <https://www.sei.cmu.edu/education-outreach/courses/course.cfm?courseCode=P72>`_. 


Using AADL
==========

The AADL language is supported by multiple tools, both open-source or commercial. The SEI maintains the `Open Source Architecture Tool Environment (OSATE) <http://osate.org>`_. All tools use the core AADL language and its extensions in several steps of the development process, such as system design, analysis, validation or implementation.

Getting Started
===============


AADL mailing lists
------------------

You can contact the AADL community through our `mailing lists <https://wiki.sei.cmu.edu/aadl/index.php/Mailing_List>`_. Mailing lists are not open to unregistered members to prevent spam and unsollicitated messages. If you would like to send a message and contact us, you would then need to register to the list that is the most relevant to your topic. You can have the details of mailing-list use on the AADL wiki.

AADL standardization committee
------------------------------

The AADL standardization committee meets four times a year in various locations accross the United States and Europe. The goals of these meetings is to meet the community, make progress on the language improvements and discuss actual and future work related to AADL. Information of the AADL meetings is available on the `standardization section <https://wiki.sei.cmu.edu/aadl/index.php/Standardization>`_ of the AADL wiki. Check out the `user days section <https://wiki.sei.cmu.edu/aadl/index.php/AADL_User_Days>`_ that contains many useful materials (including demo and presentations) from AADL users.

If you would like to attend and/or participate on the AADL standardization committee meeting, please contact us on our mailing lists. We welcome all contributions and are always looking for innovative work and new contributions.

Conferences and Research activities
-----------------------------------

Model-Based Engineering has many impact on the different aspects of software development. Many technologies are using the language for system design, validation, analysis or code generation. You can find AADL-related articles in many scientific conferences and events. We maintain `a list <https://wiki.sei.cmu.edu/aadl/index.php/AADL-Related_Conferences>`_ of coming and past scientific conferences/events related to the technology.

The AADL community organize the Architecture-Centric Virtual Integration (ACVI) workshop. Details about the event and its `past editions are available online <http://www.aadl.info/aadl/acvi/>`_.

.. toctree::
   :maxdepth: 2
   :caption: Contents:

Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
