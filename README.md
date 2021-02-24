# Setup
* Set bundle identifier and signings
* Place "GoogleService-Info.plist" to "app" folder
* Pod version 1.10.1
# 7.7.0 .Steps:
* Change versions to 7.7.0 on Pod file
* pod install
* `-ObjC` is not on `Other Linker Flags`
* Run `app (prod release)`
* `Analytics v.7.7.0 started` is missing

# 7.4.0 Steps:
* Change versions to 7.4.0 on Pod file
* pod install
* `-ObjC` is on `Other Linker Flags`
* Run `app (prod release)`
* `Analytics v.7.4.0 started` is printed
