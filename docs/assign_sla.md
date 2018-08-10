# assign_sla

Assign a Rubrik object to an SLA Domain.

```py
def assign_sla(object_name, sla_name, object_type=None)
```

## Arguments
object_name {str} -- The name of an object (ex. vSphere VM) you wish to assign to an SLA Domain.

sla_name {str} -- The name of the SLA Domain you wish to assign an object to.


## Keyword Arguments
object_type {str} -- The type of object (ex. vmware) you are assigning to the SLA Domain. (default: {None}) (choices: {vmware})


## Returns
str -- If the object is already assigned to the SLA Domain a message to that effect will be retuned.

dict -- The full API reponse of the SLA assignment API call.


