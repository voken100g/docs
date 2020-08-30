.. _release_client_base:


Voken Proxy ClientBase
======================

You can start a Proxy-ClientBase on your desktop or laptop PC now.
It would provide a local Socks5 proxy for you, which is based on vnTUNNEL (encrypted).


Guide for Proxy ClientBase on Windows
-------------------------------------

Prepare JDK, download, unzip, edit configuration file, start.


Preparation
___________

Please make sure that the JDK has been installed on your computer.

`JDK Download`_

.. _JDK Download: https://www.oracle.com/java/technologies/javase/javase-jdk8-downloads.html


.. _first_time_to_client_base:


First time to start a ClientBase
________________________________

1. `Download ClientBase package`_ from github
2. Unzip it to a new folder
3. Edit the configuration file ``config/install.config.yml``, with just a text editor such as the NotePad

.. code-block:: yaml

   localPrivateKey: YOUR_PRIVATE_KEY
   password:
   privateKeyEncrypted: false
   localSocksPort: 5678
   defaultProxyType: global

4. Replace the ``YOUR_PRIVATE_KEY`` with your Private-Key, witch you had generated before
5. Click the ``start.bat`` to run


Open dashboard
______________

Open your browser, and visit ``http://localhost:8080``, you will see it there.

On the left, choose a ProxyContainer and click ``connect``, then a Socks5 proxy on port ``5678`` is ready.

And also, you can check your balance, or make transactions here.

.. note::

   Please just ignore the LEAN-MODE UI.

   You can preview the latest version of UI here on github: https://voken100g.github.io/web-ui-clientbase

   It will be applied in a future version.


How to use a Socks5 proxy
-------------------------

Hmmm... you can ask google first.


.. _Download ClientBase package: https://github.com/voken100g/proxy-clientbase/releases/tag/v0.7.26_beta
