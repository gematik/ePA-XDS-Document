<img align="right" width="250" height="47" src="images/Gematik_Logo_Flag_With_Background.png"/> <br/>    
 
# Release Notes ePA XDS Document
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
### changes
- added http header-parameter for soap messages of IHE operations for EU-Access 
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
