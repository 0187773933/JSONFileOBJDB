# JSONFileOBJDB

```
import JSONFileOBJDB
from pathlib import Path
OurDB = JSONFileOBJDB.create({
		"save_path": str( Path( Path.cwd() , "test.json" ) )
	})
print( OurDB.self )
```

## or 

```
import JSONFileOBJDB
from pathlib import Path
OurDB = JSONFileOBJDB.create({
		"posix_obj": Path( Path.cwd() , "test.json" )
	})
print( OurDB.self )
```
