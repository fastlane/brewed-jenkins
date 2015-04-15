# Brewed Jenkins 🍺

You installed Jenkins using `homebrew`, and still want it to properly auto start in the context of the main user for easier code signing and Keychain Access? Introducing `Brewed Jenkins`.

First, install Jenkins using `brew install jenkins`

To enable auto start for Jenkins, follow this guide:

- Download [Jenkins App](https://github.com/fastlane/jenkins-app/releases/download/1.0/Jenkins.zip) and extract it somewhere save on your Mac and follow these steps:
- Open System Preferences
- Open `Users & Groups`
- Switch to `Login Items`
- Click the `+`
- Choose the Jenkins file you just downloaded

Celebrate 🎉

![Users & Groups](screenshots/users.png)
![Select Jenkins](screenshots/filechooser.png)
