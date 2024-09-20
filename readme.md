### instalacion en amd64
```sh
git clone https://github.com/pacoDan/personalizacionTermuxAndroid.git ~/Downloads/personalizacionTermux && cd ~/Downloads/personalizacionTermux && chmod +x install.sh && ./install.sh
```

```sh
wget https://bin.equinox.io/c/bNyj1mQVY4c/ngrok-v3-stable-linux-amd64.tgz
sudo tar -xvzf ngrok-v3-stable-linux-amd64.tgz -C /usr/local/bin 
# Run the following command to add your authtoken to the default ngrok.yml configuration file.
ngrok config add-authtoken 2G4xo9bF8weamzf8IP90qsyvDJY_4B4SkUp9V1nfjfptUArXK
ngrok http --domain=touching-ghost-sadly.ngrok-free.app 80
```