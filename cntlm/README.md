# Cntlm Config

## Mac OS X

* Install HomeBrew
* Open a terminal and type:

   ```brew install cntlm```

* To always launch at startup:

   ```sudo cp -fv /usr/local/opt/cntlm/*.plist /Library/LaunchDaemons```
   ```sudo chown root /Library/LaunchDaemons/homebrew.mxcl.cntlm.plist```

* To launch immediately:

   ```sudo launchctl load /Library/LaunchDaemons/homebrew.mxcl.cntlm.plist```