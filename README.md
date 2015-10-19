# openmrs-code-style-idea

Code formatting rules for [OpenMRS](http://openmrs.org) core and module developers who use IntelliJ IDEA. The rule
set has two goals:

 * Java code formatting rules that follow the OpenMRS rules defined at 
   [OpenMRS Docs](https://wiki.openmrs.org/display/docs/Code+Style) and, more specifically, by the formatting rules 
   packaged in
   [openmrs-tools](http://mavenrepo.openmrs.org/nexus/content/repositories/releases/org/openmrs/tools/openmrs-tools/)
 
 * Java and XML formatting rules that match, where the aforementioned rules do not say otherwise, the default rules
   used by Eclipse


## Compatibility

The code style file has been created with IDEA 14. Compatibility with other versions has not been tested.


## Using the rule set

Importing the rule set into IDEA is as simple as:

 1. Copy the file openmrs-code-style-idea.xml under `<INTELLIJ_HOME>/config/codestyles/`

 2. Start/restart IDEA

 3. Go to: Settings > Editor > Code Style

 4. Select "openmrs-code-style-idea" from the Scheme drop down


## Contributing

Pull requests and bug reports are welcome!