# Resource Configuration and Native Image Compilation

This sample is used to demonstrate the various ways in which resources can be declared and how they are recognized during native image compilation. 

**Current Status**:

Using Classloader classes works well when referencing resources during native image build whereas using a full classpath of the resource has no effect even eith resource configuration (resource-config.json). Reference: https://github.com/oracle/graal/blob/master/docs/reference-manual/native-image/Resources.md
