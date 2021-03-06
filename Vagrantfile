Vagrant.configure ("2") do |config|

    config.vm.box = "ubuntu/bionic64"

    config.vm.provision "shell", inline: <<-SHELL
        sudo apt-get update
        sudo apt-get install build-essential
        sudo apt-get install \
            python-dev \
            python3-minimal \
            python3-pip \
            python3-dev \
            python3-venv
        sudo apt-get update
        pip3 install --upgrade pip
        pip3 install pandas matplotlib    

    SHELL

end