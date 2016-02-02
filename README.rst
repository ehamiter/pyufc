pyufc
#####

A Python wrapper for API access to the UFC fighter roster

*Inspired by https://github.com/valish/ufc-api*

.. image:: https://img.shields.io/pypi/v/pyufc.svg
    :target: https://pypi.python.org/pypi/pyufc
    :alt: Latest PyPI version

Installation::

    pip install pyufc

Usage::

    In [1]: from pyufc import Fighter
    
    In [2]: f = Fighter()
    
    In [3]: f.get_fighter("randy couture")
    
    In [4]: f.summary

    Out[4]: u'World class wrestler, great clinch'
    
    In [5]: f.record

    Out[5]: u'19-11-0'
    
    In [6]: f.twitter_url

    Out[6]: u'http://twitter.com/Randy_Couture'
