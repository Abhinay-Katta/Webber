# Webber
## a simple voice system tray assistant app that takes voice input and searches on the default browser.
![image](https://github.com/abhikatta/Webber/assets/76813100/25ee8111-154a-4dc0-8ede-c7c862de6cd9)


![image](https://github.com/abhikatta/Webber/assets/76813100/25cc7135-0670-4eab-ae05-474d1c110aea)

# Compilation:
1. Open Terminal
2. Run command:
```
pyinstaller Webber.py --noconsole --datas=[('Webber.ico','./')] 

```
That's it!

## NOTE: If you want to open webber on system login, you can add it to start-up apps by following below steps:

1. Press `Win+r` on your computer
2. type in
   ```
   shell:startup
   ```
3. Add Webber.exe to this folder.
   And you're done!