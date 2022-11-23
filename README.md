# norminette
how to install norminette in macOS

make sure you have python installed ```python3 --version```, you will reacive a message like this(if you have it installed): ```Python 3.8.9```
next check if you have pip installed ```pip --version```, if you don't have it install it. next install norminette: ```python3 -m pip install norminette```
assuming it was succesfull go to root check the path for your norminette dir using ```python3 -m pip uninstall norminette```. You'll get the path, mine is ```/Users/(username)/Library/Python/3.8/bin/norminette``` and will ask ```Proceed (y/n)?```(answer n) and crate a ```.zshrc``` file with the leading path: ```export PATH=$PATH:/Users/(username)/Library/Python/#.8/bin/``` >>>do not enter norminette<<< like: ```export PATH=$PATH:/Users/(username)/Library/Python/#.8/bin/norminette/```. Next refresh ```source .zshrc``` and test if its working :)
