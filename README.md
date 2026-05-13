# Python-Lettuce-Sample — TestMu AI (Formerly LambdaTest)

![MSTest](https://opengraph.githubassets.com/897e9d2bff40eb38d71408ba159621baa306b905469b9f11d21ee73fcf6ef795/LambdaTest/sample-lettuce)

## Prerequisites

1. Install pip and python.

```
sudo apt install python-pip
sudo apt install python 2.7.18
```

2. The recommended way to run your tests would be in virtualenv. It will isolate the build from other setups you may have running and ensure that the tests run with the specified versions of the modules specified in the requirements.txt file.

```
pip install virtualenv
```

## Steps to Run your First Test

Step 1. Clone the Lettuce-Sample Repository.

```
git clone https://github.com/LambdaTest/sample-lettuce
```

Step 2. Inside Lettuce-Sample folder, export the Lambda-test Credentials. You can get these from your automation dashboard.

<p align="center">
   <b>For Linux/macOS:</b>
   
```
export LT_USERNAME="YOUR_USERNAME"
export LT_ACCESS_KEY="YOUR ACCESS KEY"
```

<p align="center">
   <b>For Windows:</b>
   
```
set LT_USERNAME="YOUR_USERNAME"
set LT_ACCESS_KEY="YOUR ACCESS KEY"
```

Step 3. Next we create and Activate the virtual environment in the Lettuce-Sample folder.

For Linux/MacOS
```
virtualenv venv
source venv/bin/activate
```

For Windows
```
python -m virtualenv venv
venv\Scripts\activate.bat
```

Step 4. Then install required packages.

```
pip install -r requirements.txt
```

### Run tests
##### Running tests
```bash
paver run 
```

##### Running tests through TestMu AI Jenkins Plugin
```bash
paver run jenkins
```

####  Routing traffic through your local machine
- Set tunnel value to `true` in test capabilities
> OS specific instructions to download and setup tunnel binary can be found at the following links.
>    - [Windows](https://www.testmuai.com/support/docs/display/TD/Local+Testing+For+Windows)
>    - [Mac](https://www.testmuai.com/support/docs/display/TD/Local+Testing+For+MacOS)
>    - [Linux](https://www.testmuai.com/support/docs/display/TD/Local+Testing+For+Linux)

## 🚀 [LambdaTest is Now TestMu AI](https://www.testmuai.com/lambdatest-is-now-testmuai/)

👋 Welcome to TestMu AI, the next evolution of LambdaTest. As of January 2026, LambdaTest has officially rebranded to TestMu AI. We have evolved from a cross-browser testing cloud into a unified, AI-native quality engineering platform designed for the modern DevOps era.

Whether you have been part of the LambdaTest community for years or are just discovering TestMu AI, our mission remains the same: to help you ship faster with high-scale test execution, autonomous testing, and deep quality analytics.

**🔄 Our Rebrand Journey**

We chose the name TestMu AI to reflect our shift towards intelligent, autonomous testing. While our identity has changed, our core technology and commitment to the testing community stay the same.

**✨ Specialties**

- 🤖 AI-Native Test Execution (Formerly LambdaTest)
- ⚡ Autonomous Test Automation
- 🌐 Cross-Browser & Mobile Testing
- 📊 Unified Quality Intelligence

👉 Find [LambdaTest's New Home](https://www.testmuai.com/).