# Web3-Django-Scripts
Template for Web3.py scripts running on a Django backend


<p float="left">
  <img src="https://miro.medium.com/max/1400/1*XCUD4_6FdYaZgM4b8FbjUg.png" width="300" />
  <img src="https://res.cloudinary.com/practicaldev/image/fetch/s--CAO2792J--/c_imagga_scale,f_auto,fl_progressive,h_420,q_auto,w_1000/https://dev-to-uploads.s3.amazonaws.com/i/fvuom63fat7aizcktlm3.png" width="400" /> 
</p>


## Development instructions
Using Python 3.7.9

1. install requirements:

```python
python -m pip install -r requirements.txt
```
2. add 'local_settings.py' inside project/ with the following keys:
```python
INFURA_API_KEY      = "YOUR_KEY_HERE"
ETHERSCAN_API_KEY   = "YOUR_KEY_HERE"
OPENSEA_API_KEY     = "YOUR_KEY_HERE"
OPENSEA_API_KEY2    = "YOUR_KEY_HERE"
ALCHEMY_API_KEY     = "YOUR_KEY_HERE"
ETH_ADDRESS_LIST = [
    "0xADDRESS_HERE",
    "0xADDRESS_HERE",
    "0xADDRESS_HERE",
    ...
]
```
3. to run scripts using django configuration:
```python
python scripts\web3_X.py 
```
4. to run local django server:
```python
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
```
