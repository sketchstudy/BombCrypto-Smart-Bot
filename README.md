  
# About:
  This is a BombCrypto game bot that automatically logs in, and sends the heroes to play.
  I would be very appreciated if you can donate some bucks.

### Smart Chain Wallet:
#### bc1qd9hve72m4xcrvh06zlgyngwfzupr47sude76q4

# Installation:
### Download and install Phython from the [site](https://www.python.org/downloads/). Python3.12~3.17 is preferred. 

If you download from the site it is important to tick the option "add python
to path":
![Check Add python to PATH](https://github.com/mpcabete/BombCrypto-Smart-Bot
/raw/ee1b3890e67bc30e372359db9ae3feebc9c928d8/readme-images/path.png)

### Download the code as a zip file and extract it.

### Copy the path of the bot directory:

![caminho](https://github.com/mpcabete/BombCrypto-Smart-Bot
/raw/main/readme-images/address.png)

### Open the terminal.

Press the windows key + R and type "cmd":

![launch terminal](https://github.com/mpcabete/BombCrypto-Smart-Bot
/raw/main/readme-images/cmd.png)

### cd into the bot directory:
Type the command:

```
cd <path you copied>
```

![cd](https://github.com/mpcabete/BombCrypto-Smart-Bot
/raw/main/readme-images/cd.png)

### Install the dependencies:

```
pip install -r requirements.txt
```

  
![pip](https://github.com/mpcabete/BombCrypto-Smart-Bot
/raw/main/readme-images/pip.png)

### It is finished! Now to run the bot you just need to type:

```
python index.py
```

![run](https://github.com/mpcabete/BombCrypto-Smart-Bot
/raw/main/readme-images/run.png)


# How to use?

Open the terminal, cd into the folder if you haven't yet:

```
"cd" + path
```

To run it use the command

```
python index.py
```

As soon as you start the bot it will send the heroes to work. In order to make it work, the game window needs to be visible.
It will constantly check if it needs to login or press the "new map" button. 
In 15 minutes, it will send all heroes to work again.


# Send home feature:

## How to use it:
Screenshot the heroes to be sent home in the directory: /targets/heroes-to-send-home


## How it should behave:
It will automatically load the screenshots of the heroes when starting up.
After it clicks in the heroes with the green bar to send them to work, it will look if there is any of the heroes that are saved in the directory in the screen.
If tit finds one of the heroes, the bot checks if the home button is dark and the work button is not dark.
If both these conditions are true, it clicks the home button.

----------------

## If you find my work helpful, please consider supporting the project with a small donation. Your support helps me continue developing and improving it. ❤️

### Wallet:
#### bc1qd9hve72m4xcrvh06zlgyngwfzupr47sude76q4
