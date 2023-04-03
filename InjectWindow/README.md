This project was written in collaboration with Assistant (chat.openai.com). I'd like to give Assistant co-author credit on this. I have provided the source code for the process injection, compilation instructions, some of my raw sessions with chat.openai.com, and wrote the accompanying blog here: https://teach2breach.io/coding-with-ai/ 

This isn't some FUD payload, though I did test it against Defender. It has room for improvements, especially when it comes to OPSEC. I do not recommend using this on red team ops as is. Be smart. Enhance and customize it for your needs. 

The process injection is a proof-of-concept that uses EnumWindows to enumerate user-land processes for targeting with remote process injection. It does not spawn a sacrificial process. It could be easily modified to change the injection without affecting the enum. Again, customize it for your own needs.

Enjoy and take some time to play with chat.openai.com and provide research feedback as a programmer, so we can keep enjoying it.
