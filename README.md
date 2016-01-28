### Instructions for downloading and use ###
1. Make sure you're working with the dev branch and not the master branch. This is important!
2. Make sure you have the SourceTree program installed.
3. Click the big "Check out in SourceTree" button.
4. If this is your first time downloading the source, or you need to start fresh, select the "Clone New" tab in the "URL Actions" window that will pop up.
5. Pick where you want to store the files.
6. Wait forever and a day for the 2.3 gigabyte download to finish.
7. The .uproject file will not work out of the box; You'll need to build the program, which you can do by opening up Unreal Engine, and finding the .uproject file.
8. DON'T START WORKING, you still have not set up source control in the editor. 
9. Up at the top, you'll see a drop-down that says "Source Control". Click it, and then click "Connect to source control". 
10. Set the provider to "git". You may think UE4 has crashed, but just give it a few minutes.
11. Make sure the locations that UE4 has found are correct, and click "Accept Settings".
12. You should get a message in the lower right corner of the screen saying that the connection to source control was successful.
13. You're done! congratulations!
14. Unless your part of the programming team. If you are, then you're not out of the woods yet, because as it is now, you don't have the .sln file that VS needs.
15. To generate a .sln file, go to your .uproject file, right-click, and select "Generate Visual Studio project files".