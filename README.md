## Step1: Create a folder for Cursor
```bash 
mkdir -p ~/Applications/cursor
```
## Step2: Download Cursor IDE for linux system:
```bash
wget -O ~/Applications/cursor/cursor.AppImage "https://downloader.cursor.sh/linux/appImage/x64"
```
this was saved to the folder above
## Step3: Execute AppImage 
```bash
chmod +x ~/Applications/cursor/cursor.AppImage
```
## Step4: Create symlink to acess cursor from terminal
```bash
sudo ln -s ~/Applications/cursor/cursor.AppImage /usr/local/bin/cursor
```
## Step5: Open it :D
```bash:
cursor --no-sandbox
```

