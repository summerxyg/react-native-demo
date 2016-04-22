# react-native-demo

项目描述

---

## 安装

- [Node Version Manager](https://github.com/creationix/nvm#installation)
  ```
  wget -qO- https://raw.githubusercontent.com/creationix/nvm/v0.31.0/install.sh | bash
  ```

- Node
  ```
  nvm install node && nvm alias default node
  ```

- React Native
  * 注意将npm仓库源切换到淘宝国内镜像
  ```
  npm install -g react-native-cli
  npm config set registry https://registry.npm.taobao.org
  npm config set disturl https://npm.taobao.org/dist
  ```

- Git
  ```
  sudo apt-get install git
  ```

- Android
  * [安装jdk](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)
  ```
  tar -xvzf jdk-8u91-linux-x64.tar.gz -C ~/dev/app/
  ```
  * .bashrc中设置JAVA_HOME
  ```
  export JAVA_HOME=~/dev/app/jdk1.8.0_91
  export PATH=$JAVA_HOME/bin:$PATH
  ```
  * [安装Android SDK](https://developer.android.com/sdk/installing/index.html) 国内用户点[这里](http://androiddevtools.cn/)
  * 设置ANDROID_HOME
  ```
  export ANDROID_HOME=~/dev/app/android-sdk
  ```