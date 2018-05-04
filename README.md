# mac-jdk-install-doc
document for install jdk in mac OS

# 安裝多個版本的jdk

## 步驟如下：

   1. 安裝 cask
     
   ```code 
    brew install cask
   ```

   2. 用cask install 不同版本的jdk
   
   ```code
    brew update

    brew cask install caskroom/versions/java6

    brew cask install caskroom/versions/java8
   ```

   3. 安裝jenny
   
   ```code
    brew install jenv
   ```
   並且把以下加入 ～/.bash_profile

   ```code 
    if which jenv > /dev/null; then eval "$(jenv init -)"; fi
   ``` 
   
   然後利用以下指令把 所安裝的 jvm路徑加入 jenv

   ```code
    jenv add /Libray/Java/JavaVirtualMachines/java-1.8.0.144/Content/Home
   ```
   最後利用 jenv global設定Default java 版本
   
