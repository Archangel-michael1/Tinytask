
	 		
Home	
|
Download	
|
Support	
|
FAQ / About
 
TinyTask FAQ
Frequently Asked Questions

• How did you get this program so small?
• Who is the TinyTask programmer?
• What is the difference between the .EXE, .ZIP, and SETUP downloads?
• How do I stop playback / use with games / etc etc...?
• Can I sell or distribute my compiled programs made with TinyTask?
• Why is the Help so sparse?
• Will you please add [some feature]?
• Any upgrade announcements?  What's the future of TinyTask?
 
 
 
How did you get this program so small?
Fun Fact: The graphics in TinyTask (icons, toolbars) take up half of the app size, the actual program itself is only 16 kB.
① C programming  - just pure C on a command line.
② Native OS API calls were used exclusively, which has the additional benefit of creating a hyper-fast program. No Java / .NET / plugins / EXE packers or anything else contaminates the purity that is TinyTask.
③ Careful choice of variable data storage size and resource (graphics) optimization for absolute minimum overhead.
④ Balance of compiler optimization switches for compact code generation.
⑤ Some interesting proprietary technical advances, that remain trade secrets.
TL;DR   Written with a fanatical obsession for zero code bloat.

 
Who is the TinyTask programmer?
I'm just some guy, you know?  actually, more precisely, some guy who is lazy and also happens to know C-coding, which resulted in creating TinyTask to do my work for me - and now your work too!  Everybody wins.
I had the opportunity to work on a NASA mission as a student.
I don't own a car.
I have big hair.
And it is very gratifying to hear that my laziness has helped other people.  :)

 
What is the difference between the .EXE, .ZIP, and SETUP downloads?
There is a single file that is the TinyTask program ("tinytask.exe") that is the self-contained 32-bit app. The various formats are different ways of packaging the same file.
The "tinytask.zip" file just contains tinytask.exe in compressed form, which can be useful for environments where downloading executable files is blocked. Windows can natively extract this file by double-clicking it.
The "tinytask_setup.exe" option is a standard Windows installation file. It installs TinyTask to its own Program Files folder and Start Menu app, optionally adds a desktop icon, and also includes an uninstall capability. This is the typical application package you would get for commercial software. The brilliant Inno Setup was used to create the install package, which TinyTask has supported with donations multiple times.
If you're not sure which one to get, then the .exe download is the best choice.

 
How do I stop playback / use with games / etc etc...?
Listed on the Support page.

 
Can I sell or distribute my compiled programs made with TinyTask?
Sure! There are no royalties or any restrictions. Live long & profit, have fun.
(Remember the TinyTask programmer when you're rich and famous and hiring.)

 
Why is the Help so sparse?
A program 33kb in size doesn’t leave much space for verbose documentation - most other programs' icons alone are bigger. But it is definitely a legitimate complaint about the lack of Help docs. A conscious effort was made to keep the app ridiculously simple & basic, and thus hopefully require almost no documentation.
Apologies for any confusion and/or aggravation this may have caused you. Hopefully you can embrace the "self-discovery" approach with this software.
 
Will you please add  [some feature]?
Since it's not a commercial product, TinyTask is developed when time and motivation permits. If you absolutely want to, you can send ideas to info@tinytask.net. Of course, any request that adds significant size to the program is opposite the TinyTask philosophy and will probably get vetoed.

 
Any upgrade announcements?  What's the future of TinyTask?
Actually, yes, quite a few enhancements are planned for this software. I'm usually running a Beta version as my daily driver. But publicly announcing a release date virtually guarantees that problems will happen. It's best to let TinyTask grow organically, like it was originally created.
Encouraging feedback plus contributions are very effective motivators, and help to advance this project. You can directly influence new TinyTask updates. 
