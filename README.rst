=====================================
Electrum Ravencoin
=====================================

**Electrum Ravencoin** is a lightweight and fast client for Ravencoin, designed to provide users with a secure and efficient way to interact with the Ravencoin blockchain. Based on the proven Electrum architecture, it is the ideal choice for those who need high speed, low resource requirements, and ease of use.

Badges
------
.. image:: https://img.shields.io/github/v/release/ravinbrown/Electrum-Ravencoin.svg?style=for-the-badge
   :alt: Release
   :target: https://github.com/ravinbrown/Electrum-Ravencoin/releases/tag/v4.2.1

.. image:: https://img.shields.io/github/license/ravinbrown/Electrum-Ravencoin.svg?style=for-the-badge
   :alt: License
   :target: https://github.com/ravinbrown/Electrum-Ravencoin/blob/master/LICENCE

Introduction
------------

- **License**: MIT License  
- **Author**: Thomas Voegtlin  
- **Language**: Python (>= 3.8)

Downloads
=========

.. container:: center

   .. list-table:: Platform Downloads
      :header-rows: 1
      :widths: 33 10 33
      :align: center

      * - **macOS**
        - **Windows**
        - **Linux**
      * - `Download for macOS <https://github.com/ravinbrown/Electrum-Ravencoin/releases/tag/v4.2.1>`_
      * - `Download for Windows <https://github.com/ravinbrown/Electrum-Ravencoin/releases/tag/v4.2.1>`_
      * - `Download for Linux <https://github.com/ravinbrown/Electrum-Ravencoin/releases/tag/v4.2.1>`_

   .. container:: download-buttons
      :align: center

      .. image:: https://img.shields.io/badge/Download-macOS-8A2BE2?style=for-the-badge&logo=macos&logoColor=white
         :target: https://github.com/ravinbrown/Electrum-Ravencoin/releases/tag/v4.2.1
         :alt: Download for macOS
         :align: center

      .. image:: https://img.shields.io/badge/Download-Windows-FF4500?style=for-the-badge&logo=microsoft&logoColor=white
         :target: https://github.com/ravinbrown/Electrum-Ravencoin/releases/tag/v4.2.1
         :alt: Download for Windows
         :align: center

      .. image:: https://img.shields.io/badge/Download-Linux-2E8B57?style=for-the-badge&logo=ubuntu&logoColor=white
         :target: https://github.com/ravinbrown/Electrum-Ravencoin/releases/tag/v4.2.1
         :alt: Download for Linux
         :align: center


Getting Started
---------------

To install dependencies and run from source, follow these steps:

1. **Install system dependencies:**

      sudo apt-get install libsecp256k1-dev
      sudo apt-get install python3-pyqt5  # for Qt interface
      sudo apt-get install python3-cryptography  # for cryptography

2. **Install Python dependencies:**

      python3 -m pip install --user ".[gui,crypto]"

Running from tar.gz
------------------
If you downloaded the official tarball, simply run:

      ./run_electrum

Alternatively, to install:

1. **Install required packages:**


      sudo apt-get install python3-setuptools python3-pip

2. **Install Electrum using pip:**

      python3 -m pip install --user .

Development Version
-------------------
To run the development version:

1. **Clone the repository:**

      git clone https://github.com/ravinbrown/Electrum-RVN-Ravencoin.git

2. **Install dependencies:**

      python3 -m pip install --user -e .

To run tests, use:

      pytest electrum/tests -v

Contributing
------------

Contributions are welcome! Whether it's testing, bug reporting, fixing issues, writing tests, or helping with new features, all assistance is appreciated. You can communicate on GitHub or join the development discussions on IRC at the #electrum channel on Libera Chat.
