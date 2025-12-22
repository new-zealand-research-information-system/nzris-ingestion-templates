Please refer to the full version of the Data Specification for specifics regarding field requirements  
  
# **[Provider ID_Dataset #]_grants.csv**

The grants.csv file is used to collect and organise key information about grants, contracts, and payments. It captures details such as titles and descriptions, financial values, and important dates including award, start, and end dates.  All columns are required.

**Column 1. - "id"**  
**Column 2. -	"type"**  
**Column 3.	- "category"**  
**Column 4.	- "c-protected"**  
**Column 5.	- "title"**  
**Column 6. - "start-date"**  
**Column 7.	- "end-date"**  
**Column 8.	- "description"**  
**Column 9.	- "funder"**  
**Column 10.	- "funder-reference"**  
**Column 11.	- "c-associated-grant-reference"**  
**Column 12.	- "amount-value"**  
**Column 13.	- "amount-currency-code**  
**Column 14.	- "award-date"**  
**Column 15.	- "c-recipient-organisation"**  
**Column 16.	- "labels"**  
**Column 17.	- "c-contract-reference"**  
**Column 18.	- "c-parent-contract-reference"**  
**Column 19.	- "c-funder-application-reference"**  
**Column 20.	- "c-title-language"**  
**Column 21.	- "c-alternative-title"**  
**Column 22.	- "c-intended-outcome"**  
**Column 23.	- "c-description-language"**  
**Column 24.	- "c-alternative-description"**  
**Column 25.	- "constraints"**  
**Column 26.	- "c-payment-reference"**  
  
# [Provider ID_Dataset #]_equipment.csv
The equipment.csv template is used to gather key information about the ***funds and funding rounds*** associated with research investments and grants.  All columns are required.  

**Column 1. - "id"**\
**Column 2. - "type"**\
**Column 3. - "category"**\
**Column 4. - "name"**\
**Column 5. - "c-protected"**\
**Column 6. - "description"**\
**Column 7. - "c-administering-organisation"**\
**Column 8. - "start-date"**\
**Column 9. - "finish-date"**\
**Column 10. - "c-alternative-name"**\
**Column 11. - "c-allocation-method"**\
**Column 12. - "c-vote"**  
  
# [Provider ID_Dataset #]_links.csv  
The links.csv template is used to record relationships between different categories and record types within the metadata system.  All columns are required.  

**Column 1. - "id-1"**\
**Column 2. - "category-1"**\
**Column 3. - "source-1"**\
**Column 4. - "link-type-id"**\
**Column 5. - "id-2"**\
**Column 6. - "category-2"**\
**Column 7. - "source-2"**\
**Column 8. - "privacy-level"**  	
   
# [Provider ID_Dataset #]_users.csv  
The users.csv template is used to collect information about individuals who are directly associated with research funding, such as grant recipients, collaborators, and other key contributors.  Column headings must conform to the list below. All columns are required.    
#### NOTE - unlike other ingest templates the column headings for Users require square brackets and initial caps.  
  
**Column 1. - "[Title]"**\
**Column 2. - "[Initials]"**\
**Column 3. - "[Firstname]"**\
**Column 4. - "[Lastname]"**\
**Column 5. - "[KnownAs]"**\
**Column 6. - "[Suffix]"**\
**Column 7. - "[Email]"**\
**Column 8. - "[AuthenticatingAuthority]"**\
**Column 9. - "[Username]"**\
**Column 10. - "[Proprietary_ID]"**\
**Column 11. - "[PrimaryGroupDescriptor]"**\
**Column 12. - "[IsAcademic]"**\
**Column 13. - "Protected[Generic01]"**\
**Column 14. - "ORCID[Generic02]"**\
**Column 15. - "Organisation[Generic03]"**\
**Column 16. - "JobTile[Generic04]"**  

# [Provider ID_Dataset #]_publications.csv  
The publications.csv template is used to capture information about published research outputs that result from grant funding. All columns are required.  

**Column 1. - "id"**\
**Column 2. - "type"**\
**Column 3. - "category"**\
**Column 4. - "title"**\
**Column 5. - "publication-date"**\
**Column 6. - "journal"**\
**Column 7. - "volume"**\
**Column 8. - "issue"**\
**Column 9. - "number"**\
**Column 10. - "pagination-full"**\
**Column 11. - "name-of-conference"**\
**Column 12. - "location"**\
**Column 13. - "start-date"**\
**Column 14. - "finish-date"**\
**Column 15. - "parent-title"**\
**Column 16. - "publisher"**\
**Column 17. - "edition"**\
**Column 18. - "series"**\
**Column 19. - "place-of-publication"**\
**Column 20. - "medium"**\
**Column 21. - "filed-date"**\
**Column 22. - "patent-number"**\
**Column 23. - "patent-status"**\
**Column 24. - "doi"**\
**Column 25. - "publisher-url"**\
**Column 26. - "abstract"**\
**Column 27. - "keywords"**\
**Column 28. - "notes"**\
**Column 29. - "language"**\
**Column 30. - "isbn-10"**\
**Column 31. - "isbn-13"**\
**Column 32. - "issn"**\
**Column 33. - "eissn"**\
**Column 34. - "open-access-status"**\
**Column 35. - "c-alternative-title"**\
**Column 36. - "c-alternative-description"**\
**Column 37. - "c-protected"**\
**Column 38. - "c-funding-source-reference"**  				

# [Provider ID_Dataset #]_collaborating-organisations.csv  
The collaborating-organisations.csv template is used to capture information about collaborating organisations that are directly involved in funded research activities. All columns are required.  
#### When making amendments to the list of collaborating organisations for a specified grant, the entire updated list must be provided — not just the changes. This is because each time amended data is received, the existing data is completely overwritten.  

**Column 1. - "id"**\
**Column 2. - "category"**\
**Column 3. - "field-name"**\
**Column 4. - "organisation"**\
**Column 5. - "sub-organisation"**\
**Column 6. - "street-address"**\
**Column 7. - "city"**\
**Column 8. - "state"**\
**Column 9. - "zip-code"**\
**Column 10. - "country"**\
**Column 11. - "grid-id"**\
**Column 12. - "ror-id"**\
**Column 13. - "nzbn-id"**  

# [Provider ID_Dataset #]_persons.csv  
The persons.csv template is used to capture information about individuals who are indirectly associated with research funding, such as editors and co-authors. All columns are required.  
#### When making amendments to the list of indirectly associated individuals for a specified grant or publication, the entire updated list must be provided — not just the changes. This is because each time amended data is received, the existing data is completely overwritten.  

**Column 1. - "id"**\
**Column 2. - "category"**\
**Column 3. - "field-name"**\
**Column 4. - "surname"**\
**Column 5. - "first-name"**\
**Column 6. - "order-number"**\
**Column 7. - "orcid"**\
**Column 8. - "organisation"**\
**Column 9. - "street-address"**\
**Column 10. - "city"**\
**Column 11. - "state"**\
**Column 12. - "country"**\
**Column 13. - "zip-code"**  

# [Provider ID_Dataset #]_organisations.csv  
Organisations recorded by the Research Organisation Registry [ROR](https://ror.org/) - are automatically included in the NZRIS database.  For other organisations use this template.  All columns are required.  

**Column 1. - "id"**\
**Column 2. - "type"**\
**Column 3. - "category"**\
**Column 4. - "name"**\
**Column 5. - "addresses"**\
**Column 6. - "c-alternative-name"**\
**Column 7. - "aliases"**\
**Column 8. - "acronyms"**\
**Column 9. - "url"**\
**Column 10. - "types"**\
**Column 11. - "identifiers"**\
**Column 12. - "established"**\
**Column 13. - "c-disestablishment-date"**\
**Column 14. - "parent-organisation-identifiers"**\
**Column 15. - "child-organisation-identifiers"**\
**Column 16. - "preceded-by-organisation-identifiers"**\
**Column 17. - "succeeded-by-organisation-identifiers"**\
**Column 18. - "related-organisation-identifiers"**  

