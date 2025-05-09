<img align="right" width="250" height="47" src="images/Gematik_Logo_Flag_With_Background.png"/> <br/>

# Release Notes ePA XDS Document
## information
This version 3.0.5 is the logically subsequent version of version 3.0.3 and incorporates the latest fixes, maintenance changes and changes published with version 3.1.0. 
## Release 3.0.5-5
### changes
- type of epka removed
## Release 3.0.5-4
### changes
- rename ig-eau using sub-version
## Release 3.0.5-3
### changes
- mimetype for upload of eAU is restricted to pkcs#7
## Release 3.0.5-2
### changes
- clarification regarding NFDM typecode in IG readme
## Release 3.0.5-1
### changes
- completed missing changes regarding status code for missing device registration in I_Constraint_Management_Insurant.yaml files (C_11972) 
- removed allowance of unregistered devices for PDF conversion in I_Tool_Convert_PDF_insurant.yaml
## Release 3.0.5-0
### changes
- code systems and value sets from src/vocabulary moved to terminology package on Simplifier
- added http status codes for not authorized user session in I_Constraint_Management-Insurant.yaml and I_Tools_Convert_PDF_insurant.yaml (C_11972)
- updated kbv spec for eAU IG; also formally deprecated ancient version 1.0.2.
- added requirement to use ED110104 in eventCodeList for ig-eau (C_12142)
- clarification regarding required entitlement for logging in I_Constraint_Management_Insurant.yaml (C_12051)
- added oid for code systems dicom and sct in vs-anatomic-region.xml (C_12126)
- added new port I_Document_Management_Ncpeh for EU-Access in XDSDocumentService.wsdl (C_12080)
- added format code of "Patientenkurzakte" to valueSet 1.3.6.1.4.1.19376.3.276.1.5.6 in vs-format-code.xml (C_12124)
- Definition of Terminology for elements healthProfessionalRole and healthProfessionalRolechanged changed to FHIR-Package
- fix description of category (folder) dental which in ePA 3 serves not only for "Zahnbonusheft" but for generic dental documentation as well (C_12111)
- added http header-parameter for soap messages of IHE operations for EU-Access
- integrate all changes from ePA-3.0.3:
    - correction of WSDL port definition in XDSDocumentService.wsdl (C_12068)
## Release 3.1.0-2
### changes
- reworked links to associated repositories
## Release 3.1.0-1
### changes
- integrate all changes from ePA-3.0.2-2:
    - editorial correction regarding rootDocumentId format and content in I_Constraint_Management_Insurant.yaml (C_11987)
## Release 3.1.0
release ePA-3.1.0
### changes
- integrate all changes from ePA-3.0.2-1:
    - removed paging in I_Constraint_Management_Insurant.yaml
    - editorial changes in I_Constraint_Management_Insurant.yaml and I_Tool_Convert_PDF_Insurant.yaml
    - removed unused 'Deidentifier' schema part from ig-schema-definition.json
- removed PDF/A-3 and PDF/UA from value set.
- change 'validFrom' date in ig_epka_v_1_0.json
- fixed 'displayNames' in ig-medical-image.json
## Release 3.1.0 RC
- release candidate ePA-3.1.0
## Release 3.0.2-1
### changes
- removed paging in I_Constraint_Management_Insurant.yaml
- editorial changes in I_Constraint_Management_Insurant.yaml and I_Tool_Convert_PDF_Insurant.yaml
- removed unused 'Deidentifier' schema part from ig-schema-definition.json
## Release 3.0.2
release ePA-3.0.2
### changes
- changed cardinality for documents according to ig-dpe.json, ig-nfd.json and ig-emp.json (C_11889)
- added support for childsrecord data category
## Release 3.0.2-alpha.1
- pre-release epa 3.0.2
### changes
- no changes compared to 3.0.1.2
## Release 3.0.1-2
### changes
- bugfix regex UserAgentType (C_11780)
## Release 3.0.1-1
### changes
- changed http-statuscodes from 200 to 201 in openapis (C_11811)
## Release 3.0.1
- release ePA-3.0.1
- (all changes from changelist 'ePAfueralle_3.0.1' and final review)
### changes
- bugfix: removed additionalProperties (all occurences) in I_Constraint_Management_Insurant.yaml
- removed phrase "für ePA 1.0 und ePA 2.0" from description in value-sets
- added category 'transcipts' and 'diga' in I_Constraint_Management_Insurant.yaml
## Release 3.0.1 RC
- release candidate ePA-3.0.1
### changes
- removed user specific deny policy support (C_11681)
- added api for pdf to pdf/a conversion (C_11733)
## Release 3.0.0
- release ePA-3.0
### changes
- editorial changes
- user-specific Deny Policy feature removed in concept
## Release 3.0.0 RC
- release candidate ePA-3.0
## Release 0.0.3
- initial content (pre-release ePA-3.0)
## Release 0.0.2
- initial setup branch
## Release 0.0.1
- initial setup repository
