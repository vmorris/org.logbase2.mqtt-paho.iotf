Python MQTT Client recipe for IBM Internet of Things Foundation
=

Dependecy on the Paho Python Client
http://eclipse.org/paho/clients/python/

The Paho Python Client provides a client class with support for both MQTT v3.1 and v3.1.1 on Python 2.7 or 3.x. It also provides some helper functions to make publishing one off messages to an MQTT server very straightforward.

Source
-
http://git.eclipse.org/c/paho/org.eclipse.paho.mqtt.python.git/

Download
-
The Python client can be downloaded and installed from PyPI using the pip tool:
`pip install paho-mqtt`

Building from source
-
The project can be installed from the repository as well. To do this:
```
git clone http://git.eclipse.org/gitroot/paho/org.eclipse.paho.mqtt.python.git
cd org.eclipse.paho.mqtt.python.git
python setup.py install
```
The final step may need to be run with sudo if you are using Linux or similar system.

Documentation
-
Full client documentation is available at
http://eclipse.org/paho/clients/python/docs/

