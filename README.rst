===========================
 Color Themes for ConsoleZ
===========================

Color Themes for `ConsoleZ <https://github.com/cbucher/console>`_. The color
codes are based on the PowerShell Console Colors, that you can get:

.. code-block:: posh

   PS > [enum]::GetValues([System.ConsoleColor]) | Foreach-Object {Write-Host $_ -ForegroundColor $_}

Hence it might look differently depending on the console program you use.
   
Theme List
==========

* `Spacegray <https://github.com/kkga/spacegray>`_
* Github
* Monokai
* Oblivion
* Solarized (Dark)
* Solarized (Light)
* Tomorrow
* Zenburn

HowTo
=====

* In ``Console Settings`` click on ``Import...`` and select an ``.xml`` file to
  import the color map. 

* Background and cursor colors will be set in ``<tabs>`` section, but they
  will not be imported by ``Import...``. You have to either manually copy and
  paste the relevant part into ``%appdata%\Console\console.xml`` or change the
  settings at ``Console Settings`` -> ``Tabs``.

