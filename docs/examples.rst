Examples
========

Convert from stdin to ``hello.mp3``
-----------------------------------

.. code-block:: bat

    rvtts --text "hello wold" -o hello.mp3

Convert Vietnamese text
-----------------------

.. code-block:: bat

    rvtts --text "một hai ba bốn năm sáu" -o test.mp3 -v vietnamese_female

Convert from ``chuong-0001.txt`` to ``chuong-0001.mp3`` using voice ``vietnamese_male``
---------------------------------------------------------------------------------------

.. code-block:: bat

    rvtts -i chuong-0001.txt -o chuong-0001.txt -v vietnamese_male

Print all supported voices
--------------------------

.. code-block:: bat

    rvtts --lang