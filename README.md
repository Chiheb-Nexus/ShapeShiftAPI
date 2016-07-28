# ShapeShiftAPI
A complete API wrapper written in Python3 for shapeshift.io

# Usage

**example**

```bash
├── api
│   ├── __init__.py
│   └── ShapeShiftAPI.py
└── test.py
 ```
test.py : 

```python
from api.ShapeShiftAPI import ShapeShiftAPI

class Test(ShapeShiftAPI):

	def __init__(self):
	
		ShapeShiftAPI.__init__(self)
		print(self.return_shapeshift_coins(True)) # Return all available ShapeShift coins


if __name__ == '__main__':
	app = Test()
```
