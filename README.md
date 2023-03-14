'sudo apt-get install build-essential gdb lcov libbz2-dev libffi-dev libgdbm-dev liblzma-dev libncurses5-dev libreadline6-dev libsqlite3-dev libssl-dev lzma lzma-dev tk-dev uuid-dev zlib1g-dev'  - Install libraries

'wget https://www.python.org/ftp/python/3.10.10/Python-3.10.10.tgz' - get the latest Python from Python.org website

'tar zxvf Python-3.10.10.tgz' - command to un-compress tar file

'rm Python-3.10.10.tgz' - command to remove the Python tar file imported from Python website in-order to save the space

'./configure --enable-optimizations' - command to run the optimizations by entering into Python-3.10.10.tgz directory

' make -j 4' - command to compile Python by utilizing all the 4 cores available to us

'sudo make altinstall' - command to install Python setup tools

'/usr/local/bin/python3.10' - navigate to the dir to use our locally installed Python

'vim ~/.bashrc' - to make Python default (In bash file - the I button will enable you to edit the file Hit the Esc button to exit edit mode, then enter :wq to quit and save )

'source ~/.bashrc' - to source the file so that Python-3.10.10 installed by us will always be loaded

'python -m venv ~/.venv' - create virtual environment which will live in Python-3.10.10 dir

Go to 'vim ~/.bashrc' and enter 'source ~/.venv/bin/activate' - save the bash file and exit

Once the above step is done we can see that every cell will have Python-3.10.10 version installed by us

'touch requirements.txt' - create template for our project

'touch Makefile' - create template for our project

We can install 'ludwig' AutoML tool using command 'make install' by just entering the tool name in requirements.txt file

'git status'

'git add " file name" '




