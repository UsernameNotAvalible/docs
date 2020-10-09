# List of error codes
*an error code should always have the character ``¤`` before*
### 0XX, File errors
- ``000`` not a path
- ``001`` could not find file
- ``002`` could not read file
- ``003`` is not a file
- ``004`` is not a folder
### 1XX, Command errors
- ``100`` not a command
- ``101`` not enought arguments
- ``102`` error with arguments
- ``103`` not allowed
### 2XX, Comunication errors
- ``200`` Sucsess, no reply
- ``201`` Couldn't find process
- ``202`` The process didn't reply to the manager
- ``203`` The process doesn't understand the task
- ``204`` The process couldn't execute the task
- ``205`` The task failed 
- ``206`` The manager worked as proxy and couldn't resolve the answer

