# openvisor
Suite of tools you can put on family computers so they stop getting themselves malware.

# Why
A certain few relatives of mine don't know how not to fall for malware.

# How
Well most people don't actually need to install programs, but they think they do because of that sketchy website that tells them so. This means we can just restrict that and many other functionalities of their computer to what they exactly need. There are a few different tools in the works:
- The control server. This isn't neccessary but makes things easier for the people managing their family/relatives' computers.
- A web extension. Used for attempting to block the issues at the source.
- Anti-virus style executable. Used as a second layer of defense if something attempts to make it's way onto the computer. Highly recommended to run the control server with this so you can quickly react to any detected threats that weren't able to be stopped. It also allows you to shutdown the computer before too much damage can be done.
All of these should work without any required dependencies on the other tools. Although the control server is highly recommended.

# contributor notes
If you plan on contributing something here are some things to note:
- Try to think of how you can prevent it from making this tool usable for malicious purposes. If you aren't sure of how to do that, try your best to make it as inconvenient as possible to be used for malicious purposes.
- Keep everything configurable as possible. If you even remotely think someone might need a config option for something, you should probably add it. Why? We're trying to let people customize for their exact relative's scenario, not just what fits your scenario.
- Please keep AI to a minimium, we don't need any AI making logic errors.
- Complain all you want about bad code, but if it works and its proven it works and its proven that its not too slow then womp womp. You can clean it up if you want yourself as long as it doesn't break functionality.
- Try not to make breaking changes to modules, try to keep full compatibility in some way whether it be migrating configs or just keeping backwards compatibility. 