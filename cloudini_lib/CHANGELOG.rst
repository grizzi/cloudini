^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package cloudini_lib
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.4.0 (2025-06-15)
------------------
* downgrade MCAP for compatibility with ROS2 Jazzy
* make MCAP a private dependency and copy metadata (`#17 <https://github.com/facontidavide/cloudini/issues/17>`_)
  * make MCAP a private dependency and copy metadata
  * minor cleanup
* fix buffer size in worst case scenario (`#16 <https://github.com/facontidavide/cloudini/issues/16>`_)
  Co-authored-by: Giuseppe Rizzi <giuseppe.rizzi@ascento.ch>
* Contributors: Davide Faconti, Giuseppe Rizzi

0.3.3 (2025-06-11)
------------------
* Compression profile (MCAP writer) (`#14 <https://github.com/facontidavide/cloudini/issues/14>`_)
  Co-authored-by: Giuseppe Rizzi <giuseppe.rizzi@ascento.ch>
* Null character termination (`#13 <https://github.com/facontidavide/cloudini/issues/13>`_)
* add experimental WASM + web tester
* Contributors: Davide Faconti, Giuseppe Rizzi

0.3.1 (2025-06-10)
------------------
* fix formatting
* Merge branch 'main' of github.com:facontidavide/cloudini
* small speed optimization
* fix bugs in PCL
* fix compilation on arm (`#9 <https://github.com/facontidavide/cloudini/issues/9>`_)
  Co-authored-by: Giuseppe Rizzi <giuseppe.rizzi@ascento.ch>
* Contributors: Davide Faconti, Giuseppe Rizzi

0.3.0 (2025-06-03)
------------------
* PCL conversion fixed and tested
* same speed with varint 64
* small fix
* Contributors: Davide Faconti

0.2.0 (2025-05-31)
------------------
* faster DDS decompression with less copies
* add license
* Contributors: Davide Faconti
