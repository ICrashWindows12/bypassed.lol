npm install --save-dev electron@latest
sudo npm install -g npm@10.8.1
npm install --save-dev @electron/packager
sudo npm install electron-packager -g
# Create application:
electron-packager . bypassed.lol --platform=darwin --arch=universal --asar --icon=./logo.icns

Copy and paste this. Universal script too