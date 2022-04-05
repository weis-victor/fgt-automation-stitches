# fgt-automation-stiches
Automations Stitches for FortiGate / FortiOS

# Why "Localized" Automation?
FortiGate Automation Stitches are a powerful platform for "localized" automation. But why used a localized tool instead of a centralized tool?

Centralized automation tools like FortiManager and Ansible are generally the best solution for managing distributed, complex networks, in most cases.
But there are some use cases where localized automation is preferrable or even necessary.
- Lower latency for faster response times
	- Lateral movements can happen extremely fast.
	- Every second counts when containing a compromise.
	- External automation systems often can't react fast enough.
- Self-healing can't be automated from external systems in many cases
	- Some network errors will break connectivity to external automation systems
	- In these cases, local self-healing automation is your only hope for an automated recovery
- Some smaller teams might not have access to more sophisticated automation platforms like FortiManager or Ansible
	- Localized automation tools can allow these teams a level of automation suited to their situation
	- E.g. An SMB with one FortiGate, one FortiSwitch, and two FortiAPs
