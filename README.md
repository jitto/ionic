# ionic

One time global:
```
Linux:
curl -sL https://deb.nodesource.com/setup_0.12 | sudo -E bash -
sudo apt-get install -y nodejs

Windows: https://nodejs.org/download/

npm install -g cordova ionic
```

One time project specific:
```
git clone https://github.com/jitto/ionic.git
cd ionic
ionic lib update
ionic platform browser
--ionic platform android
```

steps to test:
```
ionic serve
```
