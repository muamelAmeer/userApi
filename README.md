<h1 align="center">UserApi</h1>
<p align="center">With This Package Can You GET Info Username And Checking</p>

### Installation
You can install UserAPi using pip:
```bash
pip install userapi
```
To install the development version from Github, use the following command:
```bash
pip install git+https://github.com/muamelameer/userapi/userapi.git
```

### Example
```python

from userapi import *

print(check().Nft(user)) #To Check If UserName Is 'NFT' Or not, Result >>> True - False

print(check().Fragment(user)) #To Check If UserName Is 'Fragment.com' Or not, Result >>> True - False

print(check().Fragment(user,proxy='123.123.123')) #Check If UserName Is 'Fragment.com' Or not 'With Proxis!', Result >>> True - False

print(info().auction(user))  #To Get Information UserName If in 'Fragment.com' , Result >>> Json Data

print(info().fragment(user)) #To Get Status UserName in 'Fragment.com' , Result >>> Onauction - Sold - For Sell - ect...

print(info().fragment(user,proxy='123.123.123')) #To Get Status UserName in 'Fragment.com' With Proxis! , Result >>> Onauction - Sold - For Sell - ect...

print(info().Nft()) #To Get Information UserName If is 'NFT' , Result >>> Json Data
```
For examples, check the [examples](https://github.com/muamelameer/userapi/test.py).

# Thanks to
- You for viewing or using this project.

### Follow me on social media accounts
- [@MuamelAmeer](https://github.com/muamelameer)
- [telegram](https://t.me/forkcode)