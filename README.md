# rc522-manifest

    mkdir rc522
    cd rc522
    repo init -u https://github.com/Stuw/rc522-manifest.git
    repo sync
    cd ./usbasp-rc522/rc522
    make
    sudo cp RC522.conf /etc
    ./usbasp_read
