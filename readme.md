
<br />

## RNE(Android + iOS + [Web](https://covid19rn.vercel.app/) + Desktop)

</div>

<br />

## Introduction
Covid19 is a React-Native project developed in support of people suffering and affected due to Covid-19 {Corona} virus all around the world. The app takes a very simple and light weight design keeping in mind proper responsiveness throughout different platforms like android, iOS and web. The app lets the user track the growth of active cases in their country and provides statistics from all around the world.


This project uses [react-native-everywhere](https://github.com/sarthakpranesh/react-native-everywhere) template from version `v4.0.0`. This allows the app to be available for Android, iOS, Web and Desktop. Installable binaries for each platform is present in the latest release of the app.


<br />


| Title | Link |
| --- | --- |
| Project | https://www.figma.com/file/g9ChMLNWBmOwaKFCAv5e7C/Covid-19  |
| Prototype | https://www.figma.com/proto/g9ChMLNWBmOwaKFCAv5e7C/Covid-19?node-id=2%3A48&viewport=1246%2C-2727%2C0.8731774091720581&scaling=scale-down |

<br/>

## APIs used
1. [corona.lmao.ninja](https://corona.lmao.ninja/)

<br/>

## For Developers
To start the project follow the below common steps:
1. `git clone https://github.com/RadinaAvramova/Covid19.git`
2. `cd Covid19`
3. `yarn install`
4. `yarn start` - leave metro bundler running in another terminal

For Android:
* `yarn android` - this will start your android app

For IOS:
1. `cd ios`
2. `pod install`
3. `yarn ios` - this will start your ios app

For Web: you can close metro bundler not required for web builds
1. `yarn web` - the project will build and the site will open automatically

For Desktop:
1. `yarn web`
2. `yarn desktop`

<br/>