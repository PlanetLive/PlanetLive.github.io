# planet.live

## Using GitHub Copilot

In VS Code, click the Extensions icon on the left and [install](https://github.com/github/copilot-docs)  GitHub Copilot.

Sign-in to your GitHub account within VS Code using your profile icon in the lower left.

Check that your [copilot access](https://github.com/features/copilot/signup) is enabled. If not, join the waitlist.

Click the notification bell icon in the lower right and agree to the Copilot terms.

Paste the following in a .js page to test autocomplete:

`function findHighestNumber(array) {`

## Using Github Copilot to implement Serverless API on AWS

Additions to steps from [video](https://www.youtube.com/watch?v=t7vLF9d7gSU) by Pedram Hamidehkhan

Start a new project by choosing "File > Open..." and create a New Folder (mycopilot).  This will be your project root.

View > Terminal (ctrl`) and run a command to init. For Typescript:  

`cdk init --language typescript`

You may need to [install the AWS CDK](https://docs.aws.amazon.com/cdk/v2/guide/getting_started.html) first:

<code>npm install aws-cdk-lib</code>  
<code>npm audit fix</code>  
<code>const cdk = require('aws-cdk-lib');</code>

Error: zsh: number expected
