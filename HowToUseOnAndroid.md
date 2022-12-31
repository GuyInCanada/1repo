Firstly, you have to install Termux. To do this, you have to download the APK from [F-Droid](https://f-droid.org/repo/com.termux_118.apk).

The Google Play Store version of Termux is outdated and will not work.

After that, you have to run these commands:

```bash
curl -sLo builder.sh https://raw.githubusercontent.com/GuyInCanada/1repo/main/revanced-builder.sh
chmod +x builder.sh
./builder.sh
```

After running `./builder.sh`, it should start installing!

If you want to run it in the future, just run `./builder.sh` again.

For updating, use `./builder.sh update` and for reinstalling, use `./builder.sh reinstall` (they both do different things).

If you want to see other commands, use `./builder.sh help`

You now can build ReVanced with revanced-builder!