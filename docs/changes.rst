Change Log
==========


* 0.2.4 (dev)

  * pysftp.Connection can be used in a `with` statement
  * add .remove() method


* 0.2.3 (released 2014-05-10)

  * host code on pypi to keep pip happy
  * move code to bitbucket
  * enhance testing
  * README.rst and LICENSE named properly
  * cleaner error handling

* 0.2.2

  * additions

    * chdir(self, path) - change the current working directory on the remote
    * getcwd(self) - return the current working directory on the remote
    * listdir(self, path='.')return a list of files for the given path