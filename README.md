Install instructions:

    sudo mkdir -p /opt/theos
    echo "export THEOS=/opt/theos" >> ~/.bash_rc # or ~/.zshrc
    source ~/.bash_rc # or ~/.zshrc
    
    sudo chown -R <username> $THEOS
    git clone https://github.com/crylico/theos.git $THEOS


Required Tools:

You'll need a working version of dpkg-deb, which can be installed via brew:

    brew install dpkg
