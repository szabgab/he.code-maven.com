# Cloud-based Continuous Integration using Travis-CI

2020-08-16T19:00:01

* Travis-CI
* CI

{% embed youtube id="HMOQiRlDbPg" file="hebrew-webinar-introduction-to-travis-ci.mp4" %}


```
03:13 What is Continuous Integration? Nightly build. QA. Testing.
09:13 What is Travis-CI? Cloud-based Continuous Integration service.
11:47 How many companies use CI?  (Moshe Piamenta)
14:27 Does the CI do something different from the nightly build?
17:03 GitHub create an empty repository with only a README.md file in it.
19:20 Connect GitHub to Travis-CI, Sync if necessary, and enable a specific repository.
22:49 See the Webhook that Travis-CI creates
25:25 What is YAML? YAML Ain't Markup Language
27:17 Create .travis.yml minimal configuration
32:20 Content of the webhook
34:28 Adding the "script" field.
36:13 Failure in Travis-CI job

41:30 Minimal Travis-CI configuration and a series of Linux commands
48:15 Adding a before_script entry to make the shell script executable chmod +x
51:15 Using other versions, other distributions of Ubuntu: trusty, bionic, focal, xenial
52:38 Running on Apple Mac OSX
57:40 set -e to make the Bash script fail when of the commands fail
1:00:07 Running on MS Windows
1:00:40 The UI of Travis-CI
1:02:19 Branches
1:02:45 Build History
1:03:10 Pull Requests
1:04:20 Travis-CI scheduled jobs (TRAVIS_EVENT_TYPE=cron)  (e.g. to make sure our code does not break on new versions of our dependencies)
1:07:53 Trigger Custom Build - How to experiment with the configuration file of Travis without making changes in the Git repository.
1:10:25 Languages supported by Travis CI
1:12:30 Build status
1:14:11 Add Travis-CI Badge to the README.md file
1:15:36 Job Lifecycle: before_install, install, before_script, after_script, after_success, after_failure
1:16:57 Python
1:19:20 Python and pytest
1:21:47 Python language matrix
1:22:54 The environment variables set by Travis
1:23:38 Set environment variables
1:25:10 Python version and environment matrix
1:28:20 Matrix with several programming languages https://github.com/szabgab/slides
1:33:30 Gated push?
```

* [ערוץ יוטוב של מביני קוד](/youtube)
* [דף לינקדאין של מביני קוד](/linkedin)

