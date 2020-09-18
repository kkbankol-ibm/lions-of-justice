# Call for Code - Lightning Web Component

## Introduction

> Adding Salesforce Lightning Web Components or other Open Source Frameworks to Scale IBM Watson AI

## Code Samples

### Lions for Justice

Lions for Justice wanted to explore area where we could show scalability for non-profit and government organizations. We used the Salesforce CRM as a platform or  we integrated salesforce sites and web forms that are easy to proliferate to end users. Using vanilla carbon design we imported the framework and created media inputs so users can input additional media for our personas to upload. 

We used vanilla and standard HTML/CSS to demonstrate how easy it is to pair frontends with sophsticated backends and can aggregate data securely. In the future scalability can be shown using more advanced technologies like vueJS which was used for the main dashboard.

Being on the technical side, this journey was colassal and attention to detail was paramount we had to deal with several technologies including watson, blockchain, carbon, salesforce. So alot of different and scalable technologies; alot of fun challenges. 


# Lightning Web Components CLI
To install Lightning Web Components and the Lightning Web Components CLI, use the open source create-lwc-app tool.

The CLI steps you through a simple build setup for an app.
>npx create-lwc-app my-app
>
cd my-app
>
npm run watch

To install the CLI, you must have Node.js installed, with at least npm 5.2+. You should be familiar with either npm or yarn. The npx tool is a package runner that installs with npm 5.2+.

## Installation

> Using Microsoft Visual Studio Click on the myapp.html and use the provided html document provided. 

## Preview
>sfdx force:lightning:lwc:preview -p <platform_name> -n <component_name> [-t <target_virtual_device_name>]
-p, --platform:

Mobile platform to use for the preview. Can be either Android or iOS (not case sensitive).

>-n, --componentname:

Name of your component.

>(Optional) -t, --target:

Name of a target virtual device. This device is the iOS simulator or Android emulator configuration that hosts the preview. You can pass the name of a new or an existing device. If you enter a name that’s not recognized by the selected platform, this command creates the device using the system default configuration. If omitted, the command launches the default virtual device for the given platform.

To manage devices:

iOS: Use the Devices and Simulators tool in Xcode.
Android: Use the Android Virtual Device (AVD) Manager.
In the following Mac OS example, the name of your component is helloWorld, and you’re developing it in the ~/Projects/helloWorld/ directory.

In a Terminal window, cd to the directory of your Lightning Web Components project.
>cd ~/Projects/my-app/

Start the Lightning Web Components server.
sfdx force:lightning:lwc:start
Because the server is a synchronous process, this window doesn’t accept further command input until the server is stopped.
Leaving the server running, open a second Terminal window or Windows command prompt and enter this command:
>sfdx force:lightning:lwc:preview -p <my-app> -n <test> -t "test"

Launching the virtual device can take a few seconds. Once it has booted, Mobile Extensions presents your component in the device’s default browser. You can inspect and interact with your control. If you change visual aspects of your component’s code, the simulator immediately reflects those changes without requiring a manual refresh.
