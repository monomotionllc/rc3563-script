this is a really simple helper script for measuring cell resistances en-masse using the rc3563 tester

ensure that you have serial output enabled on the tester
settings -> #7 -> 'on'


## usage
clone the repo
install python (3.10 was what I used)
`pip install -r requirements.txt`
python ./main.py <SERIAL PORT>

you'll have to figure out how to identify which device is what, but that's on you.

## drivers

https://www.silabs.com/developer-tools/usb-to-uart-bridge-vcp-drivers?tab=downloads