# LaunchDarkly Sample Roku Application
We've built a simple application that demonstrates how LaunchDarkly's SDK works. Below, you'll find the basic build procedure, but for more comprehensive instructions, you can visit your [Quickstart page](https://app.launchdarkly.com/quickstart#/).

## Build instructions
1. In `app/components/AppScene.brs` replace your `YOUR MOBILE KEY HERE` with your Mobile SDK key and replace `YOUR FLAG KEY HERE` with your feature flag key
- to obtain the Mobile SDK go to LD UI > click your username on the lower left > select Projects > copy the Mobile key
- the flag key is under yout flag name in gray 
2. Run `make`
3. Upload `app.zip` to your device
