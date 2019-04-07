### python-sql
---
https://pypi.org/project/python-sql/

```py
from sql import *
from sql.aggregate import *
from sql.conditionals import *

user = Table('user')
select = user.select()
tuple(select)

select = user.select(user.name)
tuple(select)

select = user.select(Count(Literal(1)))
tuple(select)

select = user.select(user.id, user.name)
tuple(select)

select.where = user.name == 'foo'
tuple(select)


```

```
```

```
```


