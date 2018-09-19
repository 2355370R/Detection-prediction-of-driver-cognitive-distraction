# Detection-prediction-of-driver-cognitive-distraction
# Getting Started

## Prerequisites

### Virtual Machine (VirtualBox)

Install VirtualBox from https://www.virtualbox.org/wiki/Downloads

> Other hypervisors such as VMware and Hyper-V can be used but is not recommended. Vagrant's VMWare integration is not free and Hyper-V's setup is not as strightforward as VirtualBox.


### Virtual Machine Manager (Vagrant)

1) Install Vagrant from https://www.vagrantup.com/downloads.html

2) After installation, open a shell (Command Prompt / Terminal) and run the following command to install the Vagrant VirtualBox Guest Additions plugin:

```
vagrant plugin install vagrant-vbguest
```

3) For Windows users, you will also need to install the Windows Network File System plugin:
```
vagrant plugin install vagrant-winnfsd
```

### Server Development

Choose from one of the three following options. You are highly recommended to use option 1.

#### Option 1: Visual Studio 2017 (Highly Recommended)

1) Install Visual Studio 2017 from https://www.visualstudio.com/downloads/

2) When installing, ensure that you install the ".NET Core cross-platform development" workload.

> Visual Studio 2015 and before is not supported.

> If you already have Visual Studio 2017 installed, ensure that it is updated to version 15.4 or later. Also ensure that you have have the "ASP.NET and web development" or ".NET Core cross-platform development" workload installed.

#### Option 2: Text Editor with .NET Core SDK

1) Install a text editor such as:
    - Visual Studio Code https://code.visualstudio.com/
    - Sublime Test https://www.sublimetext.com/
    - Atom https://atom.io/

2) Install a C# plugin or extension for your text editor:
    - Visual Studio Code https://marketplace.visualstudio.com/items?itemName=ms-vscode.csharp
    - Sublime Text comes preinstalled with C# support
    - Atom https://atom.io/packages/language-csharp

3) Install the .NET Core SDK from https://www.microsoft.com/net/download/

#### Option 3: Text Editor with .NET Core SDK in Vagrant

Follow steps 1 and 2 from option 2.

### Server Testing (Postman)

Install Postman from  https://www.getpostman.com/

### Client Development

1) Install a text editor such as:
    - Visual Studio Code https://code.visualstudio.com/
    - Sublime Test https://www.sublimetext.com/
    - Atom https://atom.io/

1) Install a Babel JSX plugin or extension:
    - Visual Studio Code comes preinstalled with Babel JSX support
    - Sublime Test https://github.com/babel/babel-sublime
    - Atom https://atom.io/packages/language-babel

### Web Browser
