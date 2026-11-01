# @chaine.dance/jive-test-package

The one throwaway package Jive's package provisioning is tested with, reused for every test run. Its deploy
(`jive.library.provisionWithJive`) runs `jive login --cicd`, then `jive provision connector-package-registry
@chaine.dance/jive-test-package`, right before publishing; the jive-sh organization's configured implementation is npm. It has no other
purpose; don't depend on it.
