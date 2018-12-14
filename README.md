forissues
=======
This repository is to store the text for issues  <br></br>
***Note**: If you still have questions, please leave a comment or contact with me via `hanhaoxing@gmail.com`*<br></br>

# Contents  
- [Python](#python)   
  - [pip install](#pip-install) 
    - For: `pip install <some modoules>` doesn't work with Python3.0+ in MacOS 

# Python

## pip install
### For: `pip install <some modoules>` doesn't work with Python3.0+ in MacOS   

Especially when you are facing the issues about gcc<br></br>
And it doesn't work by entering `xcode-select --install` in terminal<br></br>
As I know, this problem is caused by the updates for MacOS, and the Apple developers have released a solution but sometimes it fails and you should fix it manually<br></br>
So, firstly, confirm that you have installed Xcode and try `xcode-select --install`  <br></br>
Then **please use** `open /Library/Developer/CommandLineTools/Packages/macOS_SDK_headers_for_macOS_10.14.pkg`  <br></br>
It should help you!<br></br>
And then, you can try `pip install <some modules>`. If there are still some problems, read the error log and use `brew doctor` to fix them.
