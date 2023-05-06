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
4. The Tabs Studio 4.7.3 explode address entrance is **0X0013D150**
5. The Tabs Studio 4.8.0 explode address entrance is **0x00141960**
6. The Tabs Studio 5.0.0 explode address entrance is **0x001322BC**
7. The Tabs Studio 5.0.1 explode address entrance is **0x001322BC**
8. The Tabs Studio 5.1.2 explode address entrance is
   - For VS2019: **0x001331DC**
   - For VS2022: **0x0013D3EC**
9. The Tabs Studio 5.2.0 explode address entrance is
   - For VS2022: **0x00144AF8**
10. The Tabs Studio 5.3.0 explode address entrance is
       - For VS2022: **0x00144B68**


