# jetson-notes


Fixes

https://stackoverflow.com/questions/52634893/importerror-cannot-import-name-gstrtspserver-introspection-typelib-not-found

```
Traceback (most recent call last):
  File "deepstream_test_1_usb.py", line 26, in <module>
    gi.require_version('GstRtspServer', '1.0')
  File "/usr/lib/python3/dist-packages/gi/__init__.py", line 130, in require_version
    raise ValueError('Namespace %s not available' % namespace)
ValueError: Namespace GstRtspServer not available

```

