# ADTools
AD tools for Windows sysadmins
David M Williams

The motivation here is to be alerted to what's changed in Active Directory and by who. This could serve as an end-of-day report to technical management to spot check issues by the HelpDesk. For example, I was working with a company that grew by acquisition so we had multiple disparate enviroments for a period of time until we integrated them. The HelpDesk would periodically add an email alias for someone in the wrong domain. It also lets you know who's being added to sensitive user groups - let's imagine Domain Admins, for example, or even Payroll.

My goal is to provide a tool that reports on what's changed and by who, and which is a command-line utility so it can be scripted, scheduled, sequenced, etc. You can find web-based on-demand reporting products from various commercial vendors already.

Another feature is to provide an option to dump AD to a snapshot file, and then be able to diff that against the current state at any later time.
