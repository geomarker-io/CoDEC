# codec_tdr

    Code
      codec_tdr()
    Output
      $property
                                                                                                                                                                                                                     profile 
                                                                                                                                                   "profile of this descriptor (always set to `tabular-data-resource` here)" 
                                                                                                                                                                                                                        name 
                                                                                                                                    "an identifier string composed of lower case alphanumeric characters, `_`, `-`, and `.`" 
                                                                                                                                                                                                                        path 
      "location of data associated with resource as a [POSIX path](https://en.wikipedia.org/wiki/Path_%28computing%29#POSIX_pathname_definition) relative to the `tabular-data-resource.yaml` file or a fully qualified URL" 
                                                                                                                                                                                                                     version 
                                                                                                                 "semantic [version](https://specs.frictionlessdata.io/patterns/#data-package-version) of the data resource" 
                                                                                                                                                                                                                       title 
                                                                                                                                                                                      "human-friendly title of the resource" 
                                                                                                                                                                                                                    homepage 
                                                                                                                                "homepage on the web related to the data; ideally a code repository used to create the data" 
                                                                                                                                                                                                                 description 
                                                                                                                                                                                       "additional notes about the resource" 
                                                                                                                                                                                                                      schema 
                                                                                                                                                                                  "a list object containing items in schema" 
                                                                                                                                                                                                                _s3VersionId 
                                                                                                                                                            "the VersionId of the file stored on AWS S3; not user-generated" 
      
      $schema
                                                                                   fields 
      "a list object as long as the number of fields each containing the items in fields" 
                                                                               primaryKey 
                             "a field or set of fields that uniquely identifies each row" 
                                                                               foreignKey 
                              "a field or set of fields that connect to a separate table" 
                                                                            missingValues 
                           "a list object, one for each column, containing the following" 
      
      $fields
                                                                                                                                                           name 
                                                                  "machine-friendly name of field/column; must be identical to name of column in data CSV file" 
                                                                                                                                                          title 
                                                                                                                          "human-friendly name of field/column" 
                                                                                                                                                    description 
                                                                                                                  "any additional notes about the field/column" 
                                                                                                                                                           type 
                   "[Frictionless type](https://specs.frictionlessdata.io/table-schema/#types-and-formats) of the field/column (e.g., string, number, boolean)" 
                                                                                                                                                    constraints 
      "[Frictionless constraints](https://specs.frictionlessdata.io/table-schema/#constraints), including `enum`, an array of possible values or factor levels" 
      

