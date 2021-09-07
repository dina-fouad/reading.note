# Configuring Django Settings
### Managing Django Settings: Issues

- Different environments.
- Sensitive data.
- Sharing settings between team members. 
- Django settings are a Python code.

## Setting Configuration: Different Approaches

### settings_local.py

The basic idea of this method is to extend all environment-specific settings in the settings_local.py file, which is ignored by VCS

### Separate settings file for each environment
This is an extension of the previous approach. It allows you to keep all configurations in VCS and to share default settings between developers.

## 12 Factors
12 Factors is a collection of recommendations on how to build distributed web-apps that will be easy to deploy and scale in the Cloud. It was created by Heroku, a well-known Cloud hosting provider.

As the name suggests, the collection consists of twelve parts:

- Codebase
- Dependencies
- Config
- Backing services
- Build, release, run
- Processes
- Port binding
- Concurrency
- Disposability
- Dev/prod parity
- Logs
- Admin processes


## SSH Tutorial

Gaining an in-depth understanding of the underlying how SSH works can help users understand the security aspects of this technology. Most people consider this process to be extremely complex and un-understandable, but it is much simpler than most people think. If you’re wondering how long it takes for a computer to calculate a hash and authenticate a user, well, it happens in less than a second. In fact, the maximum amount of time is spent in transferring data across the Internet.

Hopefully, this SSH tutorial has helped you see the way different technologies can be clubbed together to create a robust system in which each mechanism has a very important role to play. Also, now you know why Telnet became a thing of the past as soon as SSH came up.