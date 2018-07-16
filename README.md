# Hardware_UUID_Experiment_MAC
My research for changing my hardware uuid on a mac to get free stuff.
-------------------------------
#
#
## Why I started this experiment
I started this becuase of a text I saw in a discord for a cheat that uses the computers uuid the verifi that the person bought the hack.
He asked:
Can you change your uuid?
Someone replied:
Probaly only a good hacker can do that
To be honest, I am not a good hacker. But I was up for the challenge.
I replied:
Yes
#
#
#
# How I did it
First I knew I did not have the skills to change my macs uuid. I needed a vm so I can acess the files more easlily. I seacrhed for a mac software . I found it in this video on how to install mac osx on a vm.
Video:https://www.youtube.com/watch?v=1q8bQCh86js
Software: https://goo.gl/tFebLX
I installed the vm and looked through the machine files to find a file named uuid.bios. I knew this would not work but I came across this thread.
https://apple.stackexchange.com/questions/257558/how-to-modify-hardware-uuid-of-a-macos-sierra-virtual-machine-in-vmware-fusion-p
I said that just by editting (f e.g. uuid.bios = "aa aa ...") and deleting the .nvram file he was able to change it. I didint believe it and tried. Surely it did't work as I expected. I knew that the mac had some protection and kept its memory. Then I found that you can not delete the .nvram file and just delete everything inside. I changed the uuid to 73299EB6-5CDB-5992-97F8-56E39A590BA7.



# I am not responsible if you do stupid stuff.
