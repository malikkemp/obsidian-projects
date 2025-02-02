
# Steps

1. Edit all of your notes in the the separated vault, then copy the entire folder over to the content folder of this vault. This is all synced to your current POP-OS system.

2. Once everything is updated in the native vault and copied to this one, In the terminal, run the following to sync
```
npx quartz sync
```
3. To see a preview of the build, run the following command
```
npx quartz build --serve
```
4. Host your site for free on GitHub Pages