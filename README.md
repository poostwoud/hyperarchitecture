hyperarchitecture
=================
A generic architecture for hypermedia API's.

##Resource Logic Layer

Hyperarchitecture adds a resource logic layer (RLL) to the mix separating the UI and the BLL.

The RLL consists from resources and states (representations), where the states are structured according to the H-Factor (see also the hfactorclient).

**Advantages**

* BLL is abstracted away for the UI;
* RLL becomes pluggable, making it ready for the next best thing after WebAPI, or just for POH (plain old handlers);
* RLL testing is easy;

**Disadvantages**

It can feel a little WET as the controller names and methods are close to the RLL. However, this could mean creating a generic UI layer that feeds on the RLL or simply use POH's (e.g. the samples desribed in "Effective REST Services via .NET").

The first version is close to being added. So please stay tuned! :)
