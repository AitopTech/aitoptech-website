[Installation process:]
1,download the hugo binary:https://github.com/gohugoio/hugo/releases/download/v0.89.4/hugo_0.89.4_Windows-64bit.zip
2,unzip the hugo binary:unzip hugo_0.89.4_Windows-64bit.zip
3,move the hugo binary to the path:D:\personal\zhu\WebStack
4,open the cmd:cd D:\personal\zhu\WebStack
5,run the cmd to check the installation of hugo:hugo.exe version
6,clone the hugo theme:git clone https://github.com/shenweiyan/WebStack-Hugo
7,unzip the theme:unzip WebStack-Hugo.zip
8,rename the folder:WebStack-Hugo
9,move the theme to the path:D:\personal\zhu\WebStack\themes
10,copy all files in the folder:D:\personal\zhu\WebStack\themes\WebStack-Hugo\exampleSite to D:\personal\zhu\WebStack
11,run the cmd to check the installation of hugo:hugo.exe server --themesDir themes

[Local Operation process:]
1,open the cmd:
cd D:\personal\zhu\WebStack
2,run the cmd to start the server:
.\hugo.exe server
3,open the browser:
http://localhost:1313/ (bind address http://127.0.0.1:1313)
4,press Ctrl+C to stop the server

