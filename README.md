To run:
 - download chromedriver, unzip, move to `/usr/local/bin` (mac os / linux)
  ~ sudo mv ~/Téléchargements/chromedriver_linux64/chromedriver /usr/local/bin
  - sudo apt install virtualenv
  - sudo apt install python3
  - virtualenv venv
     -> " type : source venv/bin/activate "
     -> `pip install selenium`
     -> code .
  VSC will implement missing extensions.    
  

create a secrets.py file with variables:
``` 
 username = 'your_username_email'
 password = 'your_password'
```

in (venv)  -> bot.login()


                 ...if bugging, type bot.autoswipe() in (venv) console.
                 ...if the bot breaks, reload bot.autoswipe().

in (venv) ->  python -i tinder_bot.py  // To exec the script 



in Bash/zsh ->  source venv/bin/activate // To pass in venv "view"


please add more features to this, would be awesome to see what you can come up 

cheers

edited by Hkwolfx
