# rando
Some random crap

### file locations

iOS 9.0, 8.4, 8.3, 8.2, 8.1, 7.1
  - base
    - ~/Library/Developer/CoreSimulator/Devices/<identifier>/data/
  - safari plists
    - <base>/Containers/Data/Application/<identifier>/<.com.apple.mobile_container_manager.metadata.plist, com.apple.mobilesafari>
  - locationd cache plists
    - <base>/Library/Caches/locationd/cache.plist
    - <base>/Library/Preferences/com.apple.locationd.plist
  - locationd clients plists
    - <base>/Library/Caches/locationd/clients.plist
  - user settings plists
    - <base>/Library/ConfigurationProfiles/UserSettings.plist
    - <base>/Library/ConfigurationProfiles/EffectiveUserSettings.plist
    - <base>/Library/ConfigurationProfiles/PublicInfo/PublicEffectiveUserSettings.plist
  - other plists
    - <base>/Library/Preferences
  - logs
    - ~/Library/Logs/CoreSimulator/<identifier>/
    - sym linked to <base>/Library/Logs

iOS 7.1
  - base
    - ~/Library/Developer/CoreSimulator/Devices/<identifier>/data/
  - safari
    - <base>/Applications/<identifier>/Library/Preferences/com.apple.mobilesafari.plist
  - locationCache
    - <base>/Library/Caches/locationd/cache.plist
    - <base>/Library/Preferences/com.apple.locationd.plist
  - locationClients
    - <base>/Library/Caches/locationd/clients.plist
  - userSettings
    - <base>/Library/ConfigurationProfiles/UserSettings.plist
    - <base>/Library/ConfigurationProfiles/EffectiveUserSettings.plist
    - <base>/Library/ConfigurationProfiles/PublicInfo/PublicEffectiveUserSettings.plist
  - other plists
    - <base>/Library/Preferences
  - logs
    - ~/Library/Logs/CoreSimulator/<identifier>/
    - sym linked to <base>/Library/Logs
