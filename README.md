# Unencrypted-python-reverse-shell-keylogger-and-stream

dont do illegal stuff with this, ask for consent.
this is here as a proof of concept, it is discouraged to try using this to pen test or exploit vulnerabilities without consent. Btw this is likely already automatically detected by windows defender.

anyways, put your stuff in the IPPORT file in this format for the server machine details:
IPv6
IPv4
any Port to use

and you're pretty much done, custom commands are 'k1' 'k0' for keylogging, 'stream' for streaming the first display on the client's computer, 'screenshot' to take a screenshot that is saved on the server computer. It can also run normal CMD terminal commands as well.

CLIENT IS SUPPOSED TO BE RUNNING testrat (This is the end-user), SERVER (OR YOU, IF YOU WANT TO RUN COMMANDS ON THE CLIENT) IS testserver
