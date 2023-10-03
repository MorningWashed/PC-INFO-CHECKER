# PC-INFO-CHECKER

Getting Network Information:

The portion of the code starting with NetworkInterface.GetAllNetworkInterfaces() collects information about active network interfaces on the computer, including IP addresses, subnet masks, and gateways.
Getting System Information:

The code uses Environment.SystemDirectory to obtain the system directory of the operating system.
Environment.UserName returns the registered username on the system.
GetSerialNumber() retrieves the volume serial number of the system.
Environment.OSVersion provides information about the operating system version.
Other General Information:

Environment.UserDomainName gets the user's domain on the system.
GetComputerManufacturer() and GetComputerModel() attempt to retrieve information about the computer's manufacturer and model, although there were issues with these parts of the code as discussed earlier.
Environment.MachineName returns the computer's name.
GetTotalPhysicalMemory() tries to obtain the total amount of physical memory in the system.
Processor Information:

GetProcessorName() attempts to fetch the name of the processor.
GetProcessorHWID() retrieves the hardware ID of the processor.
Obtaining PC SID (Security Identifier):

GetSystemSID() retrieves the Security Identifier (SID) of the current PC.
Other Specific Information:

GetSystemSerialNumber() retrieves the system's serial number.
DateTime.Now returns the current date and time.
