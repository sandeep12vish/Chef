# Chef

### Introduction to chef
- Chef is a Configuration management tool
- Chef is an Administration tool which helps us to automate all the manual tasks.
- Chef is pull based Configuration Management Tool which is written in Ruby and Erlang
- Founder Adam Jacobs in 2009 and many later
- Earlier name was "Marionette" later renamed to Chef
- On April 2, 2019, the company announced that all their products are now open source under Apache 2.0 licence
- Chef used by Facebook, AWS opsworks, HP public cloud etc.  

### Configuration Management tool
- It is method through which we automate admin tasks
- Configuration management tool turns your code into infrastructure (IAC - frastructure as Code)
- So your code would be repeatable, testable and versionable

### Advantages of Configuration management toll
- Complete Automation
- Increase uptime
- Improve performance
- Ensure compliance
- Prevents Errors
- Reduce cost

### Chef-Architecture 
![chef-Architecture](https://user-images.githubusercontent.com/64683174/181937682-dc8ed588-269f-4021-a3e0-f5a8b421e9fb.jpg)

### Components of Chef
- Workstation:
  - Workstations are personal computers or Virtual servers, where all configuration codes is created, Tested or Changed
  - Developers/DevOps will code in workstation editor called as Recipes, And Collection of Recipe is called as Cookbooks and will send it to chef-servers 
  - Communication between Workststion and Chef-Server through CLI toll call Knife
- Chef-Server:
  - The Chef Servers is a middle-man between workstation and the nodes
  - All cookboks are stored here.
  - Server may be hosted locally are hote
- Node:
