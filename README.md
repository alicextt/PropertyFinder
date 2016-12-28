# PropertyFinder

For App Transport Security has blocked a cleartext HTTP (http://) resource load since it is insecure. Temporary exceptions can be configured via your app's Info.plist file.
Need to add 

<key>api.nestoria.co.uk</key>
<dict>
  <key>NSTemporaryExceptionAllowsInsecureHTTPLoads</key>
  <true/>
</dict>
<key>imgs.nestimg.com</key>
<dict>
  <key>NSTemporaryExceptionAllowsInsecureHTTPLoads</key>
  <true/>
</dict>

to `ios/PropertyFinder/Info.plist` to allow HTTP request

See the screenshot in Info.plist to view the corresponding change
