---
title: Log Users Out of Auth0
description: Learn how to force a user to log out of Auth0 using the Auth0 logout endpoint. 
topics:
  - logout
  - federated-logout
contentType: how-to
useCase:
  - manage-logout
---

# Log Users Out of Auth0

<%= include('../_includes/_logout-endpoint') %>

To force a logout, redirect the user to the following URL:

```text
https://${account.namespace}/v2/logout
```

Redirecting the user to this URL clears all single sign-on cookies set by Auth0 for the user.


## Keep reading
