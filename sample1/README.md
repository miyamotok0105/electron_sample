
- http://www.buildinsider.net/enterprise/electron/05

- npmのアップデート

    npm update -g npm

- electronの確認

    npm install --save-dev devtron
    electron .

- consoleでデバッグツール

    require('devtron').install()

- ビルド

    npm install -g electron-packager
    brew install wine
    electron-packager . sample1 --platform=darwin,win32,linux --arch=ia32,x64,armv7l --electron-version=1.4.14

