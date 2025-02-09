<h2 align="center">
  <br>
  <img src="https://github.com/floating/frame/raw/master/asset/png/FrameLogo512.png?raw=true" alt="Frame" width="150" />
  <br>
  <br>
  <div align="center">Frame Browser Extension :link: </div>
  <br>
</h2>

<center><p>frame.sh extension fork to inject as Metamask by default</p></center>

### Build
```bash
# Clone
› git clone https://github.com/Pentium1080Ti/frame-extension

# Install
› yarn

# Build
› yarn build
```

### Sign for Firefox
Get API keys [here](https://addons.mozilla.org/en-US/developers/addon/api/key/)
```bash
> web-ext sign --source-dir ./dist/ --api-key=xxxx:xxxxxxx:xxx --api-secret=xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
```

### Install
#### Chrome
1. Go to `brave://extensions` or `chrome://extensions`
2. Turn developer mode on if not already active (top-right corner)
3. Tap "Load unpacked"
4. Select the "dist" folder generated by running the building instructions above

#### Firefox
1. Go to `about:addons`
2. Click the gear > Install Add-on from File
3. Select `frame.xpi` from `./web-ext-artifacts`

### Related
  - [Frame](https://github.com/floating/frame) - A cross-platform Ethereum provider interface