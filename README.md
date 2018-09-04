# FASTLANE INTEGRATION IN ANDROID
This integrates fastlane integration with an android application

## Setting up FASTLANE
Run the following command in your terminal
```
brew cask install fastlane
```
or
```
sudo gem install fastlane -NV
```

## To initialise fastlane into project
In your terminal, navigate to the project directory
```
fastlane init
```

## Fastlane will not integrate or function well if UTF-8 has not been set. To set the value
```
export LC_ALL=en_US.UTF-8D    
export export LANG=en_US.UTF-8     
```

## To be able to send to slack, you will have to set up the SLACK token
```
export API_TOKEN= "your value of the API token"
```

## To send notifications about the tests that have been run
```
fastlane test
```

## To deploy the android apk to the Slack Channel
```
fastlane deploy
```

## Authors
MRM Android Team
