 .. Licensed to the Apache Software Foundation (ASF) under one
    or more contributor license agreements.  See the NOTICE file
    distributed with this work for additional information
    regarding copyright ownership.  The ASF licenses this file
    to you under the Apache License, Version 2.0 (the
    "License"); you may not use this file except in compliance
    with the License.  You may obtain a copy of the License at

 ..   http://www.apache.org/licenses/LICENSE-2.0

 .. Unless required by applicable law or agreed to in writing,
    software distributed under the License is distributed on an
    "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
    KIND, either express or implied.  See the License for the
    specific language governing permissions and limitations
    under the License.

``apache-airflow-providers-apache-kafka``
==========================================

Content
-------

.. toctree::
    :maxdepth: 1
    :caption: Guides


    Connection <connections/kafka>
    Hooks <hooks>
    Operators <operators/index>
    Sensors <sensors>
    Triggers <triggers>


.. toctree::
    :maxdepth: 1
    :caption: References

    Python API <_api/airflow/providers/apache/kafka/index>

.. toctree::
    :hidden:
    :caption: System tests

    System Tests <_api/tests/system/providers/apache/kafka/index>


.. toctree::
    :maxdepth: 1
    :caption: Resources

    Example DAGs <https://github.com/apache/airflow/tree/providers-apache-kafka/|version|/tests/system/providers/apache/kafka>
    PyPI Repository <https://pypi.org/project/apache-airflow-providers-apache-kafka/>
    Installing from sources <installing-providers-from-sources>

.. THE REMAINDER OF THE FILE IS AUTOMATICALLY GENERATED. IT WILL BE OVERWRITTEN AT RELEASE TIME!

.. toctree::
    :maxdepth: 1
    :caption: Commits

    Detailed list of commits <commits>


Package apache-airflow-providers-apache-kafka
------------------------------------------------------

`Apache Kafka <https://kafka.apache.org/>`__


Release: 1.0.0

Provider package
----------------

This is a provider package for ``apache.kafka`` provider. All classes for this provider package
are in ``airflow.providers.apache.kafka`` python package.

Installation
------------

You can install this package on top of an existing Airflow 2 installation (see ``Requirements`` below)
for the minimum Airflow version supported via ``pip install apache-airflow-providers-apache-kafka``.

Requirements
------------

===================  ==================
PIP package          Version required
===================  ==================
``apache-airflow``   ``>=2.3.0``
``confluent-kafka``  ``>=1.8.2``
===================  ==================

.. include:: ../../airflow/providers/apache/kafka/CHANGELOG.rst
