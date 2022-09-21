
# Welcome to your CDK Python project!

This is a blank project for CDK development with Python.

The `cdk.json` file tells the CDK Toolkit how to execute your app.

This project is set up like a standard Python project.  The initialization
process also creates a virtualenv within this project, stored under the `.venv`
directory.  To create the virtualenv it assumes that there is a `python3`
(or `python` for Windows) executable in your path with access to the `venv`
package. If for any reason the automatic creation of the virtualenv fails,
you can create the virtualenv manually.

To manually create a virtualenv on MacOS and Linux:

```
$ python3 -m venv .venv
```

After the init process completes and the virtualenv is created, you can use the following
step to activate your virtualenv.

```
$ source .venv/bin/activate
```

If you are a Windows platform, you would activate the virtualenv like this:

```
% .venv\Scripts\activate.bat
```

Once the virtualenv is activated, you can install the required dependencies.

```
$ pip install -r requirements.txt
```

At this point you can now synthesize the CloudFormation template for this code.

```
$ cdk synth
```

To add additional dependencies, for example other CDK libraries, just add
them to your `setup.py` file and rerun the `pip install -r requirements.txt`
command.

## Useful commands

 * `cdk ls`          list all stacks in the app
 * `cdk synth`       emits the synthesized CloudFormation template
 * `cdk deploy`      deploy this stack to your default AWS account/region
 * `cdk diff`        compare deployed stack with current state
 * `cdk docs`        open CDK documentation

Enjoy!
# Learning of First Week
## Monday (First day of training)
In the first day of training, there was orientation session presented by the professionals of SkipQ where they give a detalied overview of SkipQ training and answered our all the question. They alos presented the whole schedule of the training and what we will do during these 8 weeks.
## Tuesday (Second day of training)
### Learning outcome of the day
○ Took the introduction lecture on Amazon web services, and cloud computing in general, how amazon has the largest market share for cloud, primarily because of early deployment along with the largest footprint globally, and how their infrastructure is built, i.e. The concept of region, what I've learned to differentiate is that for a regular cloud platform other than AWS a region means a physical data center while a region for AWS really is a geographical location comprised of Availability zones with redundant power, and synchronous replication and connectivity, making it fault-tolerant and highly available.
○ Learned to differentiate between different modes of cloud services (IaaS, PaaS, SaaS)
how one has to configure which may be the best option for one's enterprise or private use.
## Wednesday (Third day of training)
### Learning outcome of the day
○ Learned how the we can provide IaC services in AWS. An essential component (arguably the backbone) of this is the AWS cloud formation, which is comprised of the Cloud   Formation Template (CFT). This can be written manually in the JSON or YAML format but the CLI/CDK is preferred as it generates default and decreases the margin of error.
○ A video provided for introduction for CDK was especially helpful in understanding why it's important.
○ I set up a Cloud-9 environment with a new EC2 instance with Ubuntu.
○ While the environment was being set-up, I used the time to accept the invitation to the GitHub repository and cloned it after forking it.
○ Cloned Git Repo in the Cloud-9 Instance
○ Initiated the Python environment.
○ Installed the AWS CDK (2.23), and Constructs in Virtual Environment
○ Saw how to access the stack once the aforementioned operations are complete
○ Generated Template file through CDK synthesize (synth)
○ Learned the use of the CDK deploy command and how it can be used to upload the stack to the cloud formation by the name initialized in "app.py". Changing in the name to avoid overriding is important
○ An alternative to approach this using TS was also discussed, which was significantly easier in my opinion
○ Finally, I pushed the code to the forked repo. A pull request was not made due to ambiguity in the requirements of this task.
## Thursday (4th day of training)
### Learning outcome of the day
○ Set up CDK (remaining) and created Lambda function (Hello World!)
○ Deployed my first Lambda function on AWS using CDK and Cloud formation template.
○ I also prepared interview question and solved leetcode problem and then watched optimization video.
# Enviornment Setup & How to run it
* First of all downloaded the Ubuntu and installed it.
* Then downloaded the VS Studio
* Then I have installed the VS studio in the window and then go to the extension of the visual studio and installed the remote development in WSL.
* Then install or upgrade the python version in the Ubuntu.
* Then download and install AWS CLI V2 in your virtual enviornment. (code is given in the week 1 resources file so no need to write down here)
* After that I clone the git repository from my github account.
* `Note`: Here use this command `git clone` and write the HTPPS web url. After that it will ask you pasword. So do not write your github pasward. Instead use the generated pasword and write down here. 
* To generate the pasword. Go to github account setting and then go to developer setting and then token access and generate the pasword.
* Create the directory structure in Ubuntu and after that write `code .` to run it on VS. `Note`: Directory creating setup is given in week 1 resources.
* Then installed the NVM and NPM.
* Now run these commands whihc are `cdk init app --language python`.Then run `python -m pip install -r requirements.txt`. Then `npm install -g aws-cdk`. Then `git add .` and `git commit -m ` to write you first commit and then `git push` and your are done with uploading your first commit.
# Lambda Function
* Then I write the lambda function and commit it over github.
* Fot this purpoes, first of all i have activate the virtual enviornment using this command `source .venv/bin/activate`. 
* Then I run the command  `cdk synth` 
* After that I run the command `cdk deploy`.
* Then run the same command which I used for first commit to get my second commit.
## Enjoy