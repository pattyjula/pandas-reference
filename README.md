# pd_reference
Reference for common pandas functions and expressions.

### Query where field  does not start with something
`df = df[~df.L_CITY_ID.str.startswith('~',na=False)]   `
### Querying multiple columns  

`df2 = df1[df1.ADLF != 0 & (df1.ADLT != 0) & (df1.ADRF != 0) & (df1.ADRT != 0)]    `

### Check for dll needs with geopandas  
`from ctypes.util import find_library`  
`find_library('geos_c')`  

Output something like: '...\\Library\\bin\\geos_c.dll'

### Git Bash  

Set a proxy:  
`git config --global http.proxy http://proxyuser:proxypwd@proxy.server.com:8080`

Check the current proxy:  
`git config --global --get http.proxy`

Proxies can also be set through Environment Variables as a Variable and Value for a user.

Create a virtual environment  
`conda create -n testenv python=3.x anaconda`  

Activate a virtual environment    
`source activate testenv`  

Deactivate  
`conda deactivate`

#### Aliases  

Creating an alias for jupyter notebook. This assumse you could not open a .bash_profile. If you can, then the command will be  `start .bash_profile`  Otherwise, run the following:    

`touch .bash_profile`  

`vim .bash_profile`  

`alias jn='jupyter notebook'`  
