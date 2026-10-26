# @chaine.dance/jive-test-package

The one throwaway package Jive's package provisioning is tested with, reused for every test run. Its deploy asks
the Jive server to provision it on npm (`jive.library.provisionWithJive`) right before publishing. It has no other
purpose; don't depend on it.
