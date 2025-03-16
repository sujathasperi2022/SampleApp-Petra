This is a sample React Native Project for exploring the deep linking connecting a dApp with Petra
Wallet app. **Currently only Android side configuration for deep linking is completed in this sample app**.

Note :: In order to test the deep linking working the device in which running the android app should have the Petra Wallet installed, signed in and connected in TestNet.

To run the project follow the below steps

1. navigate to root of project
2. Do npm install

3. To run on android

# npx react-native android

!! ATTENTION - The app tries to establish a connect with Petra Wallet through deeplinking. At the moment no direct package is available to do this.

** Reference Links **

1. [Petra Documentation on implementing deeplinking](https://petra.app/docs/mobile-deeplinks)

2. [Sample app provdied by Petra](https://github.com/aptos-labs/mobile2mobile-example)
