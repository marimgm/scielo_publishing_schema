.. _postal-code:

<postal-code>
=============

+---------------------------+--------------------+
| Aparece em                | Ocorre             |
+===========================+====================+
| :ref:`elemento-addr-line` | Zero ou mais vezes |
+---------------------------+--------------------+



Identifica o código postal da instituição vinculada ao autor, caso exista.

Exemplo:


.. code-block:: xml

    ...
    <addr-line>
        <city>São José do Rio Preto</city>
        <state>São Paulo</state>
        <postal-code>00000-000</postal-code>
        ...
    </addr-line>
    ...

.. note:: Elemento válido apenas na versão 1.1 da JATS. Consulte exemplo de declaração para a versão JATS v1.1 em `!DOCTYPE <http://docs.scielo.org/projects/scielo-publishing-schema/pt_BR/1.7-branch/tagset/xml-doctype.html>`_.

.. {"reviewed_on": "20170921", "by": "carolina.tanigushi@scielo.org"}