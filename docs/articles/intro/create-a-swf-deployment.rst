.. _create-a-swf-deployment:

Nomenclature
************

* **SWF Platform Blueprint** - Contains the overall roles, responsibilities, process, and instructions involved in working with a Yocto based Linux platform in the IVI domain. A project is intended to use the Blueprint as-is and extend it with a project specific Deployment. Imagine a layered view, where this is the bottom and most generic layer.
* **SWF Platform Deployment** - A concrete SWF that describes and documents how the project's platform is developed. A SWF Platform Deployment re-uses the SWF Platform Blueprint for the generic parts that are not project specific, i.e. it extends the Blueprint.
* **Software Factory (SWF)** - This is a term used within the SWF Platform Deployment to refer to itself. This is not additional documentation, but rather a convenient term.
* **Platform** - The exact content and definition of what a platform is, is project specific.
