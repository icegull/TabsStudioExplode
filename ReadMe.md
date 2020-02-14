If you don't know what's Tabs Studio, please skip it.

And this article is just for research, please don't use it in commercial.

How to explode: 

1. Download dnSpy: https://github.com/0xd4d/dnSpy/releases?tdsourcetag=s_pctim_aiomsg

2. Open the TabsStudio.dll, you might see it in VS plugin folder like:
   C:\Users\AAAAA\AppData\Local\Microsoft\VisualStudio\16.0_ca87153b\Extensions\bvrpto1s.nxn\

3. Choose "IL" in title bar and query "verify_reg" in the Find windows and you will see:

   ![image](https://github.com/icegull/TabsStudioExplode/blob/master/dnSpy.jpg)

4. The explode address entrance is **0x0013BFA0，12 04** (This is based on Tabs Studio 4.6.1)

5. Now edit the TabsStudio.dll via Hex tool **12 04** to **16 2A** and save

6. Done



1. The Tabs Studio 4.6.1 explode address entrance is **0x0013BFA0**
2. The Tabs Studio 4.7.0 explode address entrance is **0X0013CE70**
3. The Tabs Studio 4.7.1 explode address entrance is **0X0013CF60**
