# EJS Partials

![Image](https://hdivsecurity.com/img/security-bugs.jpg)


> Partials come in handy when you want to reuse the same HTML across multiple views. Think of partials as functions, they make large websites easier to maintain as you don’t have to go and change a piece of text in every page it appears in. Instead, you define that reusable bundle of code in a file andinclude it wherever you need it.


## Note: The <%- %> tags allow us to output the unescaped content onto the page (notice the -). This is important when using the include() statement since you don’t want EJS to escape your HTML characters like ‘<’, ‘>’


## How to use partial?
> - Write your code in a file with es extension
> - Put the dile inside views folder.
> - write this code where you want to insert the code `<%- inculde('folderName/ fileName.ejs') %>`.

