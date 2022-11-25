
### securityContext: setting in deployment(s)

the securityContext: setting is a workaround to access the local cluster volume folders
whose user is "algo:algo" (groupid = 1001). 

see: https://stackoverflow.com/questions/43544370/kubernetes-how-to-set-volumemount-user-group-and-file-permissions

A more general/configurable way must be found.


