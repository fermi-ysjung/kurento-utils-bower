[![License badge](https://img.shields.io/badge/license-Apache2-orange.svg)](http://www.apache.org/licenses/LICENSE-2.0)
[![Documentation badge](https://readthedocs.org/projects/fiware-orion/badge/?version=latest)](https://doc-kurento.readthedocs.io)
[![Docker badge](https://img.shields.io/docker/pulls/fiware/orion.svg)](https://hub.docker.com/r/fiware/stream-oriented-kurento/)
[![Support badge]( https://img.shields.io/badge/support-sof-yellowgreen.svg)](https://stackoverflow.com/questions/tagged/kurento)

[![][KurentoImage]][Kurento]

Copyright 2018 [Kurento]. Licensed under [Apache 2.0 License].

[Kurento]: https://kurento.org
[KurentoImage]: https://secure.gravatar.com/avatar/21a2a12c56b2a91c8918d5779f1778bf?s=120
[Apache 2.0 License]: http://www.apache.org/licenses/LICENSE-2.0



Kurento Utils for Bower
=======================

The Kurento Utils project contains a set of reusable components that have been found useful during the development of the WebRTC applications with Kurento.



Installation instructions
-------------------------

Be sure to have installed [Node.js](https://nodejs.org/en/) and [Bower](https://bower.io/) in your system:

```bash
curl -sL https://deb.nodesource.com/setup_4.x | sudo bash -
sudo apt-get install -y nodejs
sudo npm install -g bower
```

To install the library, it's recommended to do that from the [Bower repository](https://bower.io/search/):

```bash
bower install kurento-utils
```

Alternatively, you can download the code using Git and install manually its dependencies:

```bash
git clone https://github.com/Kurento/kurento-utils-bower
cd kurento-utils-bower
npm install
```



About Kurento
=============

Kurento is an open source software project providing a platform suitable for creating modular applications with advanced real-time communication capabilities. For knowing more about Kurento, please visit the Kurento project website: https://www.kurento.org.

Kurento is part of [FIWARE]. For further information on the relationship of FIWARE and Kurento check the [Kurento FIWARE Catalog Entry]. Kurento is also part of the [NUBOMEDIA] research initiative.

[FIWARE]: http://www.fiware.org
[Kurento FIWARE Catalog Entry]: http://catalogue.fiware.org/enablers/stream-oriented-kurento
[NUBOMEDIA]: http://www.nubomedia.eu



Documentation
-------------

The Kurento project provides detailed [documentation] including tutorials, installation and development guides. The [Open API specification], also known as *Kurento Protocol*, is available on [apiary.io].

[documentation]: https://www.kurento.org/documentation
[Open API specification]: http://kurento.github.io/doc-kurento/
[apiary.io]: http://docs.streamoriented.apiary.io/



Useful Links
------------

Usage:

* [Installation Guide](http://doc-kurento.readthedocs.io/en/stable/user/installation.html)
* [Compilation Guide](http://doc-kurento.readthedocs.io/en/stable/dev/dev_guide.html#developing-kms)
* [Contribution Guide](http://doc-kurento.readthedocs.io/en/stable/project/contribute.html)

Issues:

* [Bug Tracker](https://github.com/Kurento/bugtracker/issues)
* [Support](http://doc-kurento.readthedocs.io/en/stable/user/support.html)

News:

* [Kurento Blog](https://www.kurento.org/blog)
* [Google Groups](https://groups.google.com/forum/#!forum/kurento)



Source
------

All source code belonging to the Kurento project can be found in the [Kurento GitHub organization page].

[Kurento GitHub organization page]: https://github.com/Kurento



Licensing and distribution
--------------------------

Copyright 2018 Kurento

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
