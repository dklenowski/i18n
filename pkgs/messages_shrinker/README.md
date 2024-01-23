The data file treeshaker for [`package:messages`](../messages/README.md).

This is to be used together with the `const_finder` from the Dart SDK (to be added). The `const_finder` will find all const instances in the treeshaken kernel file (in the VM) or Codegen World (in the Dart2Js compiler) and output them to a file. This file can be consumed by this package to remove all non-referenced messages from the data file.