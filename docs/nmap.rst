NMAP Usage
==========

Finding Live Hosts
------------------

  $ nmap -sn 10.0.0.1/24
  
  -sn   do not port scan
  10.0.0.1/24   scan entire subnet 10.0.0.0
  
yang ni contoh result

.. code-block:: console
  
  $ nmap -sn 10.0.0.1
  # Nmap 7.10 scan initiated Mon May 09 14:59:34 2016 as: Z:\PentestBox\bin\Nmap\nmap.exe -T3 -oA default dmp.p1.com.my
  Nmap scan report for dmp.p1.com.my (122.255.96.14)
  Host is up (0.0015s latency).
  Not shown: 997 filtered ports
  PORT     STATE SERVICE
  80/tcp   open  http
  443/tcp  open  https
  9080/tcp open  glrpc

  # Nmap done at Mon May 09 14:59:41 2016 -- 1 IP address (1 host up) scanned in 14.06 seconds

.. code-block:: python

  def bubble_sort(items):
    """ Implementation of bubble sort """
    for i in range(len(items)):
        for j in range(len(items)-1-i):
            if items[j] > items[j+1]:
                # Swap!
                items[j], items[j+1] = items[j+1], items[j]

.. code:: python

  def bubble_sort_code(items):
    """ Implementation of bubble sort """
    for i in range(len(items)):
        for j in range(len(items)-1-i):
            if items[j] > items[j+1]:
                # Swap!
                items[j], items[j+1] = items[j+1], items[j]


.. highlight:: python

  def bubble_sort_highlight(items):
    """ Implementation of bubble sort """
    for i in range(len(items)):
        for j in range(len(items)-1-i):
            if items[j] > items[j+1]:
                # Swap!
                items[j], items[j+1] = items[j+1], items[j]


* yang ni lagi la pening.... tak dak tollbar langsung

.. image:: https://upload.wikimedia.org/wikipedia/commons/2/28/S10.08_Gizeh%2C_image_9627.jpg
