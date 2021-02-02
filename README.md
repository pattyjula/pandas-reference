# pd_reference
Reference for common pandas functions and expressions.

### Query where field  does not start with
`df1 = df1[~df1.L_CITY_ID.str.startswith('~',na=False)]   `
### Querying multiple columns  

`df2 = df1[(df1.ADLF != 0) & (df1.ADLT != 0) & (df1.ADRF != 0) & (df1.ADRT != 0)]    `