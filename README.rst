octopus.io 프로젝트
===================

octopus.io 프로젝트는 octopus의 한글 매뉴얼을 영문화하기 위해 생성되었다.

개요
-----------------

이 프로젝트는 문서화 도구인 Sphinx(http://sphinx-doc.org/index.html)를 통해 문서를 생성한다. Sphinx는 reStructuredText 포맷을 사용하고, 테마는 sphinx_rtd_theme을 적용했다. 

빌드
-----------------

이 프로젝트를 빌드하는 방법은 다음과 같다.

1. sphinx를 설치하기 위해서는 먼저 easy_install을 설치해야 한다. easy_install의 설치 및 확인하는 방법은 다음과 같다.

.. code-block:: bash

    $ sudo yum install python-setuptools
    $ easy_install --version

2. easy_install를 사용하여 Sphinx를 설치한다. 설치하는 방법은 다음과 같다.

.. code-block:: bash

    $ sudo easy_install -U Sphinx

3. sphinx를 이용하여 빌드한다. 빌드하는 과정은 다음과 같다.

.. code-block:: bash

    $ git clone https://github.com/bitnine-oss/octopus.io.git
    $ cd ocotpus.io
    $ make html


4. 확인은 _build/html/index.html 파일을 통해 가능하다. 확인하는 과정은 다음과 같다.

.. code-block:: bash

    $ cd _build/html/
    $ cat index.html




