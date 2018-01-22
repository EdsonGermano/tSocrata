# tSocrata
Socrata Talend Connector
Authors: Peter Moore

## Setup with Talend
Download and install [Open Studio for Data Integration](https://www.talend.com/products/data-integration/)

For Mac you may have to run it from the command line:
`$ cd TOS_DI-{your version}/TOS_DI-macosx-cocoa.app/Contents/MacOS/
$ ./TOS_DI-macosx-cocoa`

## Setup development components
Clone this repository into a folder called "custom_components"

Follow the instructions [here](https://help.talend.com/reader/Jkvp187bw8jcmAsfn~skJQ/Cp2O1jasCRNKAlFAmCHSdw) for installing and updating custom components

## Using the Component
Allows for common datasync functions:
- Replace
- Upsert
- Append
- Delete

More information on using datasync can be found at [dev.socrata.com](http://socrata.github.io/datasync/)

Human readable field names will be converted into api field names and exactly matched so that the field name "New Column" will match the Socrata column with the api field name "new_column"

## Next Steps
- Dataset create method
- Composite location columns
