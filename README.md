# Offensive MacOS
This is a collection of macOS specific tooling, blogs, and other related information for offensive macOS assessments.

## Tools

### JavaScript for Automation (JXA)
* https://github.com/D00MFist/PersistentJXA
* https://github.com/D00MFist/Custom_URL_Scheme
* https://github.com/D00MFist/InjectCheck
* https://github.com/D00MFist/Dylib-Hijack-Scanner
* https://github.com/its-a-feature/Orchard
* https://github.com/its-a-feature/HealthInspector
* https://github.com/FSecureLABS/CalendarPersist

### C2 Frameworks/Agents
* https://github.com/mishmashclone/BC-SECURITY-Empire
  * latest branch of the Empire framework with a Python-based payload for macOS
* https://github.com/cedowens/MacShellSwift
* https://github.com/cedowens/MacShell
* https://github.com/its-a-feature/Mythic/tree/master/Payload_Types/apfell/agent_code
  * JXA agent for the Mythic framework
* https://github.com/its-a-feature/Mythic/tree/master/Payload_Types/poseidon/agent_code
  * Golang agent for the Mythic framework that uses a lot of CGO with macOS API calls
* https://github.com/Marten4n6/EvilOSX
* https://github.com/neoneggplant/EggShell

### Binaries
* https://github.com/cedowens/SwiftBelt
  * Swift tool for doing safety checks on a macOS host for red teaming
* https://github.com/xorrior/xpcutil
  * Tool for sending XPC messages to launchd
* https://github.com/Tyilo/insert_dylib
  * Tool for injecting dylib weak/strong headers into a Mach-O binary
* https://github.com/its-a-feature/bifrost
  * Tool for interacting with Kerberos on macOS

### Other
* https://github.com/cedowens/Mythic-Macro-Generator
  * tool to generate Microsoft Office Macros for running Mythic's apfell payload
* https://github.com/cedowens/macOS-browserhist-parser
  * tool for parsing macOS browser history on disk
* https://github.com/xorrior/macOSTools
  * repo of a lot of macOS tooling
* https://github.com/its-a-feature/macos_execute_from_memory
  * starter code to run macos code from memory
* https://github.com/herrbischoff/awesome-macos-command-line
  * Lots of commandline based actions that aren't necessarily offensive, but can be pretty handy
* http://newosxbook.com/ent.jl
  * Web resource of entitlements for macOS binaries

## Blogs
* https://www.mdsec.co.uk/2018/08/escaping-the-sandbox-microsoft-office-on-macos/
* https://wojciechregula.blog/post/learn-xpc-exploitation-part-3-code-injections/
* https://wojciechregula.blog/post/abusing-electron-apps-to-bypass-macos-security-controls/
* https://scriptingosx.com/2018/04/demystifying-root-on-macos-part-1/
* https://www.xorrior.com/
* https://www.dssw.co.uk/reference/authorization-rights/
* https://www.trustedsec.com/blog/macos-injection-via-third-party-frameworks/
* https://blog.xpnsec.com/bypassing-macos-privacy-controls/
* http://lockboxx.blogspot.com/2019/10/macos-red-teaming-211-dylib-hijacking.html
* https://theevilbit.github.io/posts/
* https://desi-jarvis.medium.com/office365-macos-sandbox-escape-fcce4fa4123c
* https://posts.specterops.io/sparkling-payloads-a2bd017095c
* https://posts.specterops.io/audio-unit-plug-ins-896d3434a882
* https://posts.specterops.io/no-place-like-chrome-122e500e421f
* https://posts.specterops.io/persistent-credential-theft-with-authorization-plugins-d17b34719d65
* https://posts.specterops.io/folder-actions-for-persistence-on-macos-8923f222343d
