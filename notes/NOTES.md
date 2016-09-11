Needed to do this on my Mac MINI (OS X 10.11):
```
gem install nokogiri -- --with-xml2-include=/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX10.11.sdk/usr/include/libxml2 --use-system-libraries
```

Found this via https://github.com/sparklemotion/nokogiri/issues/1486

Really:
```
gem install nokogiri -v '1.6.8' -- --with-xml2-include=/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX10.11.sdk/usr/include/libxml2 --use-system-libraries
```

