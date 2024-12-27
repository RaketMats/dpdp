# About
How are different design models, that are quite abstract, realised, how are they implemented, what is the end result. 

One of the modelling languages used here, is Edgy, aimed for enterprise design and which consists of a set of 'elements' which build an abstract model of a business or organisation or actually more or less any kind of construct with people involved. These elements are grouped into 'facets' which represents the different aspects of the endevour at hand. The resulting model(s) can then also be 're-framed' i.e viewed from different perspectives such as from user or people perspective down to the technical implementation, or from the business perspective towards peoples need and technical solution to find out whether is it economically feasible.

So how are these Edgy Elements implemented. Some are easy, the 'Facets' represents different aspects such as 'capability' and 'process' which maps to a base class of a Sundblad style 'capability and process services' respectively. 'Asset' can be seen a 'information' or 'data' and thus modelled as an 'information object' with access functions/API's of various kind. 
And 'task', 'channel' and 'journey' can maybe be modelled the same as 'capability' and 'process', but with different roles, becuase this is really what it is, different perspective for the different roles, which Coplien also talks about in 'Lean Architecture'.
Then 'people', 'outcome', 'activity' and 'object' is more tricky. Maybe just model as use-cases, service blueprints et al, but software? Maybe 'use case services', and different 'users' or 'roles'. But how to model 'outcome' in c++/Python? 'Asset' is easy, it is a kind of 'data' or 'information'.

The 're-framing' or different 'viewpoints', i.e. viewing the model form 'Product' or 'People' or 'Architecture' perspective can be modeled via instantianting different objects from base classes or iheritance from a more generic/root or abstract base class to different sub-classes which in turn can be abstract.

Implementation are done in c++ and Python. Using c++ if for the greater nuances possible and Python because it is easier to understand.
