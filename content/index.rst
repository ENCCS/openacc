OpenACC training
================

.. prereq::


.. toctree::
   :maxdepth: 1
   :caption: Table of contents

   0.01_gpu-introduction
   1.01_openacc-introduction
   1.02_openacc-heat-equation
   2.01_openacc_profiling
   2.02_openacc_optimization

.. toctree::
   :maxdepth: 1
   :caption: Reference

   quick-reference
   guide



.. _learner-personas:

Who is the course for?
----------------------

This training is for students, researchers, engineers and programmers
who would like to quickly get started with GPU programming using
OpenACC.  Some previous experience with C/C++ or Fortran
is required, and the lesson furthermore assumes that participants have
some familiarity with the following topics:

- Logging in to supercomputers and using a bash terminal
- Compiling C/C++ or Fortran codes using compilers and makefiles
  

About the course
----------------

This lesson is an introduction to GPU programming using the
directive-based OpenACC paradigm. The course consists of lectures, type-along and hands-on
exercises. Topics covered include the architecture of the GPU
accelerators, basic usage of OpenACC, and how to control data
movement between CPUs and GPUs. Basic optimization of the code will
also be covered. 

After the course the participants should have the basic skills needed
for utilising OpenACC with new or existing programs.

The participants are assumed to have knowledge of Fortran and/or C
programming languages. Since participants will be using HPC clusters
to run the examples, fluent operation in a Linux/Unix environment is
assumed.

See also
--------

There are many excellent resources online for learning OpenACC.
To name only few:

- Official `OpenACC site <https://www.openacc.org/>`_
- `CSC training resources on OpenACC <https://github.com/csc-training/openacc/>`_

Credits
-------

The lesson file structure and browsing layout is inspired by and derived from
`work <https://github.com/coderefinery/sphinx-lesson>`_ by `CodeRefinery
<https://coderefinery.org/>`_ licensed under the `MIT license
<http://opensource.org/licenses/mit-license.html>`_. We have copied and adapted
most of their license text.

Several examples and exercises in this lesson have been adapted from the following
sources:

- `GPUBootcamp Official Training Materials <https://github.com/gpuhackathons-org/gpubootcamp>`_
- `CSC OpenACC training material <https://github.com/csc-training/openacc>`_

Instructional Material
^^^^^^^^^^^^^^^^^^^^^^

All ENCCS instructional material is made available under the `Creative Commons
Attribution license (CC-BY-4.0)
<https://creativecommons.org/licenses/by/4.0/>`_. The following is a
human-readable summary of (and not a substitute for) the `full legal text of the
CC-BY-4.0 license <https://creativecommons.org/licenses/by/4.0/legalcode>`_.
You are free:

- to **share** - copy and redistribute the material in any medium or format
- to **adapt** - remix, transform, and build upon the material for any purpose,
  even commercially.

The licensor cannot revoke these freedoms as long as you follow these license terms:

- **Attribution** - You must give appropriate credit (mentioning that your work
  is derived from work that is Copyright (c) ENCCS and, where practical, linking
  to `<https://enccs.se>`_), provide a `link to the license
  <https://creativecommons.org/licenses/by/4.0/>`_, and indicate if changes were
  made. You may do so in any reasonable manner, but not in any way that suggests
  the licensor endorses you or your use.
- **No additional restrictions** - You may not apply legal terms or
  technological measures that legally restrict others from doing anything the
  license permits. With the understanding that:

  - You do not have to comply with the license for elements of the material in
    the public domain or where your use is permitted by an applicable exception
    or limitation.
  - No warranties are given. The license may not give you all of the permissions
    necessary for your intended use. For example, other rights such as
    publicity, privacy, or moral rights may limit how you use the material.
  
Software
^^^^^^^^

Except where otherwise noted, the example programs and other software provided
by ENCCS are made available under the `OSI <http://opensource.org/>`_-approved
`MIT license <http://opensource.org/licenses/mit-license.html>`_.

