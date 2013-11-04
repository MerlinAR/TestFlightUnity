# TestFlightUnity

A Unity Plugin for the [TestFlight SDK](https://testflightapp.com/sdk/).

# Features
This plugin supports:
* Session registration.
* Checkpoints.
* Custom environment information.
* The feedback view.
* Sending feedback via the SDK.
* Setting the device ID (for non-app store builds only).
* Logging.
* Deliberate crashes to test the crash handler.

# Usage

First download and extract all the SDK files from here: https://testflightapp.com/sdk/download/

To use the sample app:
 1. Put all the TestFlight SDK files into unity/Assets/Plugins/iOS.
 1. Find your SDK Token by going to the TestFlight website, selecting your app and clicking on "App Token" in the sidebar.
 1. Open up the ExampleTestFlight scene in unity/Assets/TestFlight.
 1. Select the ExampleTestFlight object in the heirarchy.
 1. Put your SDK Token into the token field in the inspector.
 1. Build and run on your device.
 1. Optionally, upload the example app to TestFlight to test all the features.

To use the plugin in your Unity project:
 1. Put all the TestFlight SDK files into your Assets/Plugins/iOS.
 2. Copy all the files from unity/Assets/Plugins/iOS into the Assets/Plugins/iOS folder in your project.
 3. Add calls to the TestFlight class in your project. Use unity/Assets/TestFlight/ExampleTestFlight.cs as a guide.
 4. Run, test and publish your app to TestFlight.

# Further Resources
Check the TestFlight SDK at https://testflightapp.com/sdk/doc/.


MIT License, see License.txt.
