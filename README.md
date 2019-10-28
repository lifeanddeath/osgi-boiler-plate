# osgi-boiler-plate

Simple example showing how osgi works. In a typical OSGi environment, we define bundles which are nothing but jar files with additional meta-data defining the given jar file to create dependencies between modules. Using osgi, we hide our implementations which are not needed to be revealed in our projects or packages and we do this by actually using interfaces. 

In this example, we have MathConsumer and MathService bundles. MathConsumer acts as a client where MathService provides the calculation service by letting the others use its interface.

Note: You need to install Eclipse Equinox plug-in to run this project and configure the run accordingly, it should be running as a OSGi Framerwork.
