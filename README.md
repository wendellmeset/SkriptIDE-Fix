# SkriptIDE-Fix
Fixes the bug when launching Skript IDE!

There is a bug in Skript IDE when launching that looks like this:
```OS: Windows 10 amd64
Java: 1.8.0_191-b12
SK-IDE version: 2019.1u4
Time: 5.4.2021 14:38:39
 org.json.JSONException: A JSONArray text must start with '[' at 0 [character 1 line 1]
     at org.json.JSONTokener.syntaxError(JSONTokener.java:505)
     at org.json.JSONArray.<init>(JSONArray.java:108)
     at org.json.JSONArray.<init>(JSONArray.java:161)
     at com.skide.utils.ResourceManager.parseSkriptVersions(ResourceManager.kt:31)
     at com.skide.utils.ResourceManager.loadResources(ResourceManager.kt:109)
     at com.skide.CoreManager$bootstrap$1$task$1.call(CoreManager.kt:105)
     at com.skide.CoreManager$bootstrap$1$task$1.call(CoreManager.kt:65)
     at javafx.concurrent.Task$TaskCallable.call(Task.java:1423)
     at java.util.concurrent.FutureTask.run(FutureTask.java:266)
     at java.lang.Thread.run(Thread.java:748)
```
This github project is a fix for it.

**Steps:**

- 1: Download the file called update.bat thats in this repository
- 2: Download the file called skide_win_x64.exe thats in this repository
- 3: Put both of those files into the installation directory of Skript IDE
- 4: open the file called update.bat
- 5: your done, now launch Skript IDE and the error should be fixed!
