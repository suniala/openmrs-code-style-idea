# openmrs-code-style-idea

Code style scheme for [OpenMRS](http://openmrs.org) core and module developers who use IntelliJ IDEA. The scheme has two 
goals:

 * Java code formatting rules that follow the OpenMRS rules defined at 
   [OpenMRS Docs](https://wiki.openmrs.org/display/docs/Code+Style) and, more specifically, by the formatting rules 
   packaged in
   [openmrs-tools](http://mavenrepo.openmrs.org/nexus/content/repositories/releases/org/openmrs/tools/openmrs-tools/)
 
 * Java and XML formatting rules that match, where the aforementioned rules do not say otherwise, the default rules
   used by Eclipse


## Compatibility

The code style scheme file has been verified to work on:
 
 * IDEA 14
 
 * IDEA 15


## Using the scheme

Importing the scheme set into IDEA is as simple as:

 1. Copy the file openmrs-code-style-idea.xml under `<INTELLIJ_HOME>/config/codestyles/`

 2. Start/restart IDEA

 3. Go to: Settings > Editor > Code Style

 4. Select "openmrs-code-style-idea" from the Scheme drop down


## Contributing

Pull requests and bug reports are welcome!