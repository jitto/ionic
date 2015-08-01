# ionic

Onetime - Windows and Mac: https://nodejs.org/download/ and https://git-scm.com/download/win

One time Linux from shell:
```
curl -sL https://deb.nodesource.com/setup_0.12 | sudo -E bash -
sudo apt-get install -y nodejs git
```

One time common from shell
```
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
