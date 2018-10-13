
# CLI (Command Line Interface)

## Links

- https://github.com/oclif/oclif
  - Node.js Open CLI Framework
- https://medium.com/@jdxcode/12-factor-cli-apps-dd3c227a0e46
  - Heroku CLI sub-commands
    - E.g: `heroku domains:add www.myapp.com`
    - > Colons are preferable to help delineate the command between the arguments passed to the command. The user quickly learns that argument 1 is the command and how to get help for it. <br><br>
        Getting into the weeds a little bit, there is another technical reason why we prefer colons. For topic-level commands like $ heroku domains we list all the domains of an app. If we used spaces to separate commands from subcommands and wanted this topic-level command to accept an argument, the parser could have no way to determine if the argument was a subcommand or argument to the topic command. Therefore, using spaces to separate makes it so you cannot have topic-commands also accept an argument.
      
  


