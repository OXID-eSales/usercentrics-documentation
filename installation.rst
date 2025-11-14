Installation
============

:productname:`OXID Cookie Management powered by usercentrics` 3.2 wird standardmäßig mit OXID eShop Compilation 7.4 ausgeliefert.

Bei einer normalen Installation müssen Sie das Modul also nicht installieren, sondern können direkt mit dem Konfigurieren loslegen.

Abhängig von Ihrer Installation des OXID eShops können Sie das Modul jedoch bei Bedarf manuell nachinstallieren.

|prerequisites|

Sie haben OXID eShop Version 7.4.

|procedure|

1. Laden Sie das Modul :productname:`OXID Cookie Management` aus dem Repository herunter und installieren Sie es.

   Führen Sie dazu im Hauptverzeichnis des Shops (in dem die Datei :file:`composer.json` liegt) folgenden Befehl aus:

   .. code:: bash

      composer require oxid-professional-services/usercentrics

2. Um das Modul zu aktivieren, tun Sie Folgendes:

   a. Wählen Sie :menuselection:`Erweiterungen --> Module`.
   b. Wählen Sie das Modul.
   c. Wählen Sie auf der Registerkarte :guilabel:`Stamm` des Moduls die Schaltfläche :guilabel:`Aktivieren`.

.. todo:: #tbd: Hinweis auf oe-console, module activation und clear cache

.. Intern: oxdajl, Status:
