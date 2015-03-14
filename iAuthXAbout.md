#iAuthX About


# Introduction #
iAuthX is a set of WebServices designed for Cloud-based implementation as a part of iCOR3 framework. It delivers core interfaces for Authentication and Authorization. It enables large enterprises and organizations to securely authentication and authorize FiD outside legacy boundaries using Cloud services.

# Related Projects #
  * [iCOR3 Project](https://code.google.com/p/icor3/)
  * [iMDirectory Project](https://code.google.com/p/imdirectory/)
  * [iQu Project](https://code.google.com/p/iqu/)

# Use Cases - Examples #
## Federate identity across several identity boundaries ##
_Fusion of two or more companies requires centralized authentication system where employees can be authenticated across several security boundaries to federated systems.
iMDirectory can work on domain level and be restricted to only several domain containers and object attributes that are required for federated identity. In this approach authentication can be implemented using claim-based identity. As sub-scope that iMDirectory can access is fully controlled on the component level risk of sensitive data leakage is minimal. This configuration is recommended for all Cloud-based implementations._
![https://imdirectory.googlecode.com/svn/wiki/Example1.gif](https://imdirectory.googlecode.com/svn/wiki/Example1.gif)
Figure 2. AuthN and AuthZ flow - Example