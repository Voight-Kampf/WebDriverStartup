#  WebDriverStartup

Credits: yifanlu, NVIDIA Corporation

On systems where it is not possible/desirable to disable system integrity protection, this 
codeless kext can be built and signed as an alternative to modifying/invalidating 
NVDAStartupWeb.kext.  It will allow Nvidia's web drivers built for a different OS to to 
load.

Note: There is no benefit to installing this extension if you have disabled SIP (or enabled --without kext), edit the NvidiaStartupWeb.kext .plist instead

External GPU users: use NVDIDIAEGPUSupport, it does the same thing and more

[NVIDIAEGPUSupport](https://github.com/pedroresende/NVIDIAEGPUSupport)
