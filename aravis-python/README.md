# Aravis python Binding


## Requirement

- pygobject
### Ubuntu
1. Execute `sudo apt install libgirepository1.0-dev gcc libcairo2-dev pkg-config python3-dev` to install the build dependencies
2. Execute `pip install pycairo to build and install Pycairo`
3. Execute `pip install PyGObject to build and install PyGObject`

### Windows



## Usage
Execute `pip install -i https://test.pypi.org/simple/ aravis-python`
### Minimum test case
```
import aravis
from aravis import Aravis
Aravis.update_device_list()
connected_num_device = Aravis.get_n_devices()
print("Device number: {} ".format(connected_num_device))
```
