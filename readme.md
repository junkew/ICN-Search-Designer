# Readme

With this small powershell script you can create ICN StoredSearches that deal with the more complex and/or pattern 
1. Writes the XML correct (whereas ICN fails to have JSON and XML in sync)
2. Not possible to edit the stored search with the ICN
3. Use at your own risk as there is not much documentation on the schemes from IBM: https://www.ibm.com/docs/en/filenet-p8-platform/5.7.0?topic=roadmap-schema-reference

## Deals with 
  (A And B And C) And <BR>
      ( <BR>
        ( D=1 And E=4 And F=7) or <BR> 
        ( D=2 And E=4 And F=7) or <BR>
        ( D=2 And E=5 And F=8) or <BR> 
        ( D=3 And E=6 And F=9) <BR>
      ) <BR>
