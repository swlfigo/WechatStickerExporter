<p align="center">
    <img src="Resources/icon.png" alt="Project Icon" width="250" />
</p>



# Wechat Sticker Exporter

A Macos App To Export Wechat Stickers

<p align="center">
    <img src="Resources/snapshot1.png" width=300 alt="Demo video" />
</p>

# System Requirements

* MacOS 14.0+

# FAQs

* Shows 'This Application is Damaged' 

​	No Code Sign For this app , use `xattr -cr /Path/To/This/.App` to Fix!

* Can't Export or Show some Stickers

  Yes, it might have some stickers url can't be loaded even in the webbrowser, there is no solution here.Wechat Macos App may have 302 redirect logic inside the code , you can find out by Reversed it.
