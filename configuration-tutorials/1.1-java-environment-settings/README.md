# 1.1 Java Environment Settings

## For Windows 10

*  Control Panel --&gt; System
*  Advanced System Settings
*  Environment Variables
*  In System Variables, create Java\_Home:

```text
"C:\Program Files\Java\jdk-11.0.1(address)"
```

*  Then create CLASSPATH:

```text
".;%Java_Home%\bin;%Java_Home%\lib\dt.jar;%Java_Home%\lib\tools.jar"
```

*  Then Edit Path: add the first line:

```text
 " "%Java_Home%\bin;%Java_Home%\jre\bin;" "
```

*  and add the last line:

```text
"C:\Program Files\Java\jdk-11.0.1(address)\bin"
```

*  Last, add the line:

```text
"%CLASSPATH%"
```

*  cmd:

```text
java -version; java; javac
```

## For MacOS

* Go to website to download: [https://www.oracle.com/technetwork/java/javase/downloads/index.html](https://www.oracle.com/technetwork/java/javase/downloads/index.html)
* Click to install the .dmg file
* Then check shell first, mine is zsh:

![](../../.gitbook/assets/image%20%2855%29.png)

* For zsh, use command `open ~/.zshrc`:
* Add the last line:`export JAVA_HOME=$(/usr/libexec/java_home)`
* Use command `source ~/.zshrc`
* Then we can check the path by command `echo $JAVA_HOME`:

![](../../.gitbook/assets/image%20%2838%29.png)

* For bash, use command:
* `open ~/.bash_profile`
* `source ~/.bash_profile`

### Java Uninstall

* In terminal:
  * `sudo rm -fr /Library/Internet Plug-Ins/JavaAppletPlugin.plugin`
  * `sudo rm -fr /Library/PreferencePanes/JavaControlPanel.prefPane`
  * `sudo rm -fr ~/Library/Application Support/Oracle/Java`
* After that, go to `/Library/Java/JavaVirtualMachines` and delete `jdk x.x.xxx`

