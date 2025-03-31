
# **F**unny **C**hromebook **E**xploit **U**sing **W**indow() **E**val

This project is inspired by [@Blobby Boi](https://github.com/Blobby-Boi), and no i did not skid anything i rewrote it to be more lightweight while doing the same impact or even more.



## How does this "***version***" work?
When you open a window using something like`const x = window.open(url)` you can call a function called `eval()` but you cant simply just evaluate a script into the website, that would just be too easy, so chrome prevents arbitrary code to be runned using this function, but you run other code that isnt evil, there are a lot of things but i wont list it all, but the way i did this was easy, while i was trying to find another way to recreate the exploit was: when you open i window, i waited until "x" was opened and then started a simple evaluate script that would replace the location with the long text, where it would try to resolve itself, i noticed that while it hanged, when you flip the ```Allow access to file URLs``` it would close the extension and then would open the long url, i dont know how to explain it. 

