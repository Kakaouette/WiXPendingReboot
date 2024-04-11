NoRebootPackage: Basic Heatwave generated package. Can be run without triggering any reboot or PendingFileRenameOperation.

NoRebootBundle: Includes NoRebootPackage as an MsiPackage. Can be run without triggering any reboot or PendingFileRenameOperation.

PendingRebootBundle: Includes NoRebootBundle as an **ExePackage**. After it finishes, a PendingFileRenameOperation is created for a .tmp file.
