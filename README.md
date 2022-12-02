# exorde-setup for myself
https://github.com/exorde-labs/ExordeModuleCLI for set-up help

using anaconda 

`apt install python3 python3-pip git screen`
`pip install --upgrade pip`

`wget https://repo.anaconda.com/archive/Anaconda3-2022.10-Linux-x86_64.sh
bash Anaconda3-2022.10-Linux-x86_64.sh
bash`

after then, type YES 

exordemodulecli install
`git clone https://github.com/exorde-labs/ExordeModuleCLI.git`

in cli folder
`cd ExordeModuleCLI`

set up
`conda create --name exorde-env python=3.9`
`conda activate exorde-env`
and install requirement
`pip install -r requirements.txt`

//// will try to work node background
` screen -r <name>`
`python Launcher.py -m <eth_addreesss> -l LEVEL_LOGGING`

i recommend log level 3
and quit. you can see logs 
`screen -r <name> `\



