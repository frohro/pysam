.. _HostDeveloper:

HostDeveloper
**************************

Wrapper for SAM Simulation Core model: `cmod_host_developer.cpp <https://github.com/NREL/ssc/blob/develop/ssc/cmod_host_developer.cpp>`_

Creating an Instance
=========================

There are three methods to create a new instance of a PySAM module. Using ``default`` populates the newclass' attributes with default values specific to a ``config``. Each technology-financialconfiguration corresponds to a SAM GUI configuration. Using ``new`` creates an instance with empty attributes. The ``wrap`` function allows compatibility with PySSC, for details, refer to :doc:`../PySSC`.

**HostDeveloper model description**

.. automodule:: PySAM.HostDeveloper
	:members:

Functions
=========================

.. autoclass:: PySAM.HostDeveloper.HostDeveloper
	:members:

Revenue Group
==============

.. autoclass:: PySAM.HostDeveloper.HostDeveloper.Revenue
	:members:

FinancialParameters Group
==============

.. autoclass:: PySAM.HostDeveloper.HostDeveloper.FinancialParameters
	:members:

SystemCosts Group
==============

.. autoclass:: PySAM.HostDeveloper.HostDeveloper.SystemCosts
	:members:

TaxCreditIncentives Group
==============

.. autoclass:: PySAM.HostDeveloper.HostDeveloper.TaxCreditIncentives
	:members:

Depreciation Group
==============

.. autoclass:: PySAM.HostDeveloper.HostDeveloper.Depreciation
	:members:

PaymentIncentives Group
==============

.. autoclass:: PySAM.HostDeveloper.HostDeveloper.PaymentIncentives
	:members:

Host Group
==============

.. autoclass:: PySAM.HostDeveloper.HostDeveloper.Host
	:members:

SystemOutput Group
==============

.. autoclass:: PySAM.HostDeveloper.HostDeveloper.SystemOutput
	:members:

ReturnOnEquity Group
==============

.. autoclass:: PySAM.HostDeveloper.HostDeveloper.ReturnOnEquity
	:members:

Moratorium Group
==============

.. autoclass:: PySAM.HostDeveloper.HostDeveloper.Moratorium
	:members:

Recapitalization Group
==============

.. autoclass:: PySAM.HostDeveloper.HostDeveloper.Recapitalization
	:members:

TimeOfDelivery Group
==============

.. autoclass:: PySAM.HostDeveloper.HostDeveloper.TimeOfDelivery
	:members:

ConstructionFinancing Group
==============

.. autoclass:: PySAM.HostDeveloper.HostDeveloper.ConstructionFinancing
	:members:

BatterySystem Group
==============

.. autoclass:: PySAM.HostDeveloper.HostDeveloper.BatterySystem
	:members:

Outputs Group
==============

.. autoclass:: PySAM.HostDeveloper.HostDeveloper.Outputs
	:members:

