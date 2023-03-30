# Customer Counter JS Code
This JavaScript code displays a customer counter on the homepage of a website.

## why i wrote this code
When you search the internet, the counter codes that you usually come across are of the type that start and end when the page is constantly refreshed. What if your page is scrollable?

I wanted to add such a feature while designing my client's site and ran into this problem. I've been browsing the internet to find out where my mistake is, but I couldn't find it. At this point I realized that my code actually works when I refresh the page, not when I hit the header with the count property. Accordingly, I revised my code again, I share it with you, I hope it will be useful.

##Features
When the user scrolls down to the area where the counter is located, the count starts and increments from 0 to a specified value (in this case, 3000). 
The code uses a "counter" class and the "data-count" attribute to get the target count from another file

