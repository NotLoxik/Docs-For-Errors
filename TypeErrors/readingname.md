## Error:
```
/workspaces/Corgi/Handlers/commandHandler.js:19
      client.commands.set(commandFile.data.name, properties);
                                           ^

TypeError: Cannot read properties of undefined (reading 'name')
    at loadCommands (/workspaces/Corgi/Handlers/commandHandler.js:19:44)
    at /workspaces/Corgi/index.js:21:5
    at processTicksAndRejections (node:internal/process/task_queues:96:5)
```
## Easy fix:
* Check if you have any empty file, if you have then delete it.
