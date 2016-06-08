#Mac终端文件夹校验

Last login: Tue Jun  7 18:11:03 on ttys002  
localhost:~ androllen$ shasum /Users/androllen/Downloads/vsc1_high.mp4  
a169c36c885556a84c7dcd1cfb09219c46b8c54f  /Users/androllen/Downloads/vsc1_high.mp4    
localhost:~ androllen$ shasum -a 256 /Users/androllen/Downloads/vsc1_high.mp4  
c8c0c8ebd8288c4846587ff2cdaa5e6bbadf4235202796889b8b3200e2360247  /Users/androllen/Downloads/vsc1_high.mp4  
localhost:~ androllen$ shasum -a 512 /Users/androllen/Downloads/vsc1_high.mp4  
9f0141b0a1a6666cfb85946842367a5dc4203c4f8bb19464f6f9bb384accb2d2ecd0e35152333338516aa651a5e3699c2d9e87b4cb1e030d788eaccdcfc73690  /Users/mahongbin/Downloads/vsc1_high.mp4  
localhost:~ androllen$ md5 /Users/androllen/Downloads/vsc1_high.mp4  
MD5 (/Users/androllen/Downloads/vsc1_high.mp4) = 109a89cef6cb874aa91792d61b9cc4fb  




relate link:  
http://osxdaily.com/2009/10/13/check-md5-hash-on-your-mac/  
http://osxdaily.com/2012/02/05/check-sha1-checksum-in-mac-os-x/  
