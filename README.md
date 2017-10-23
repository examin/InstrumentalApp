Note.* There is a known java issue, and may be solved by following the procedure suggested by MKorsch on StackOverflow (http://stackoverflow.com/questions/16428098/groovy-shell-warning-could-not-open-create-prefs-root-node):

"1. Go into your Start Menu and type regedit into the search field.
2. Navigate to path HKEY_LOCAL_MACHINE\Software\JavaSoft (Windows 10 seems to now have this here: HKEY_LOCAL_MACHINE\Software\WOW6432Node\JavaSoft)
3. Right click on the JavaSoft folder and click on New -> Key
4. Name the new Key Prefs and everything should work."