# Jakarta EE XML Deployment Descriptors

This directory contains everything necessary to build and test the Jakarta EE deployment descriptors. 

See [doc/HOWTO](doc/HOWTO.md) for directions.

The src directory contains the sources for schemas of the current version of Jakarta EE.
The tests in the test directory have been updated accordingly.

Before using these schemas for the next version of Jakarta EE, the following changes
will need to be made:

- The files will need to be renamed to use the version number of
  the corresponding spec in the Jakarta EE release.
- After building the schema, it must be published according to the guide described in [How to Publish XML Schemas](https://jakartaee.github.io/platform/publish-xml-schemas).

----

Licensing

Except where noted below, all files are licensed under the same terms as
Eclipse GlassFish and they must carry the corresponding license.

The lib/external directory contains an unaltered copy of the documents at the
following URLs:
  http://www.w3.org/2001/xml.xsd
  http://www.w3.org/2001/XMLSchema.xsd
  http://www.w3.org/2001/XMLSchema.dtd
  http://www.w3.org/2001/datatypes.dtd

The originals can be found in http://www.w3.org/2001.

W3C grants use as is, so DO NOT MODIFY THEM FOR ANY REASON.

We use the local files for testing, because importing remote files to schema
can be problematic.

The lib/jar/js.jar file contains the Mozilla Rhino scripting engine.
See https://developer.mozilla.org/en/Rhino_License for information on
the license for Rhino (a dual MPL 1.1/GPL 2.0 license).
