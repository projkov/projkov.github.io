---
layout: post
title:  "My thoughts about FHIRPath.me"
date:   2024-09-28 06:29:00 +0200
categories: open source
---
It's been a long time since the last version of [FHIRPath.me]: https://fhirpath.me was released. I’ve used this app many times in my work, and I find it convenient, especially because of its speed and sharing feature. However, I have also identified several areas for improvement. Below are my thoughts on the functionality I'd like to see in the app:

1. `Expand workspace`: I suggest removing the button that triggers the information modal window to free up more space for displaying information.
2. `Add output format selection`: Currently, there’s no option to select the output format, and the result is shown as a list of text blocks. It would be great to allow users to choose an output format where the result is displayed as a regular string, with the option to separate values using a specified delimiter—such as a period or a comma.
3. `Support multiple queries simultaneously`: At the moment, users need to open a new browser tab for each query, which can lead to losing track of the task's context. It would be more convenient if users could make multiple queries in the same window.
4. `Save expressions for reuse`: Often, expressions are repeated with slight variations in context, for example, when a user is studying the CapabilityStatement resource and wants to see different "searchParams" elements for various resource types. Adding the ability to save expressions for later reuse would enhance productivity.
5. `Enable multiple workspaces`: Users should be able to work with multiple workspaces simultaneously and store references and expressions as formalized collections that they can revisit when needed.

To implement features 3-5, backend support and user authentication will likely be required. This means expanding the tech stack to include a backend language such as Python or TypeScript, along with a database like PostgreSQL. Initially, it might be sufficient to use local storage with import/export capabilities for collections.

These suggestions will soon be turned into GitHub issues, and I hope to find time to work on them.

Best regards,

Pavel Rozhkov
