# default_permissions

/ [config](/reference/config/index.md) / [leafnodes](/reference/config/config/leafnodes/index.md) / [authorization](/reference/config/config/leafnodes/authorization/index.md) 

The default permissions applied to users, if permissions are
not explicitly defined for them.

## Properties

### [`publish`](/reference/config/leafnodes/authorization/default_permissions/publish/index.md)

A single subject, list of subjects, or a allow-deny map of
subjects for publishing. Specifying a single subject or list
of subjects denotes an *allow* and implcitly denies publishing
to all other subjects.

### [`subscribe`](/reference/config/leafnodes/authorization/default_permissions/subscribe/index.md)

A single subject, list of subjects, or a allow-deny map of
subjects for subscribing. Note, that the subject permission can
have an optional second value declaring a queue name.

### [`allow_responses`](/reference/config/leafnodes/authorization/default_permissions/allow_responses/index.md)


