# I will do below to become a entry-level beast at TALL stack by October 2nd, 2022.

- I will watch Laracasts at least 1 hour per day. I will repeat till I understand what the instructor is doing and why
  it is necessary.
- I will read this list this 3 times a day.
- I will add 10-40 items per day.
- At least 2 times a week I should learn > 30 new info.

8/24

1. `art route:list` => lists all routes in my app.
2. `|` => called "pipe". In terminal takes output of command to the left and passes it to command ot the right.
3. `grep "verify"` => Search function in terminal.
4. Conclusion(1,2,3) `art route:list | grep "verify"`
5. If I'm searching for which controller, view etc a route leads to I can
   use `art route:list | grep "route-i-am-searching-for"`
6. touch => terminal command that creates a file. example: `touch daily-notes.md `
7. `asset` => 'assets' is for .js, .css, html, pictures etc and are always saved inside public/assets. (
   e.g. `asset('build/assets/app.60fef7bc.css')`)
8. Servers run PHP, python, node.js.
9. Client runs css, js, html.
10. Hot Module Replacement( or Hot Reloading) => allows you to refresh the page when a piece of JavaScript is changed
    and also maintain the current state of the component in the browser.
11. Documentation -> have to make micro assumptions, so I can guess where the answer is located.

8/25

1. flex element in HTML => flex property sets the flexible length on flexible items. Flexbox items are the immediate
   children in a flex container.
2. CSS transition => allows you to change property values smoothly(backround color, size, letter colour, etc.), over a
   given duration.
3. Tailwind CSS( utility framework) => you don't have to write custom CSS to style your application. Instead, you can
   use utility classes to control the padding, margin, color, font, shadow, and more of your application.
4. tailwind.config.js => By default, Tailwind will look for an optional tailwind.config.js file at the root of your
   project where you can define any personal customizations.
5. Css Position property => specifies the type of positioning method used for an element and has to be set first(
   available values: static, relative, fixed, absolute, sticky).
6. After ^ elements are positioned using the top, bottom, left, and right properties that work differently
   depending on the position value.
7. `justify-between` => utility to justify items along the flex container’s main axis such that there is an equal amount
   of space between each item.
8. `cursor-pointer`(Tailwind CSS) => utility for controlling the cursor style when hovering over an element
9. `npm run` =>  I can see the available options in package.json "scripts".
10. `npm install` => installs your application's frontend dependencies.
11. `npm run dev` => ( old) used to run the mix module, which is used to compile the JavaScript and CSS files
12. `npm run build` => ( new) modern frontend build tool that provides an extremely fast development environment and
    bundles your application's CSS and JavaScript files into production ready assets.
13. HTML `<head>` Element => is a container for metadata (document title, character set, styles, scripts, and other meta
    information) and is placed between the <html> tag and the <body> tag.
14. ^ Metadata is not displayed.

8/26

1. CSS Pseudo-element( inside `app.css`) => is used to style specified parts of an element( e.g. Insert content before,
   or after, the content of an element. Style the first letter, or line, of an element)
2. HTML `form` => is used to collect user input. The user input is most often sent to a server for processing
3. `x-data` => use of Alpine
4. Alpine =>  enables you to harness the reactive and declarative nature of popular frontend libraries and frameworks(
   Angular, React, Vue) at a much lower cost
5. Tailwind => is a power pack of everything you need to create a website without writing any custom CSS.
6. Livewire => is a full-stack framework for Laravel that makes building dynamic interfaces simple, without leaving the
   comfort of Laravel( coded like PHP).
7. DTO( database transfer object) => is an object that carries data between processes. It facilitates communication
   between two systems (like an API and your server) without potentially exposing sensitive information
8. `composer update` =>
    - Read composer.json
    - Remove installed packages that are no more required in composer.json
    - Check the availability of the latest versions of your required packages
    - Install the latest versions of your packages
    - Update composer.lock to store the installed packages version
9. `composer install` =>
    - Check if composer.lock file exists (if not, run composer-update and create it)
    - Read composer.lock file
    - Install the packages specified in the composer.lock file
10. CSRF ( cross-site request forgery) token =>is a secure random token (e.g., synchronizer token or challenge token)
    that is used to prevent CSRF attacks.
11. CSRF exists because web applications trust the cookies sent by web browsers within an HTTP request.
12. CSRF attack => the attacker causes a victim's browser to make a request that results in a change or action which
    benefits the attacker (and/or harms the victim) in some way.

8/29

1. Every web page of the internet uses HTML,CSS, Javascript. These are the foundational languages of the internet and
   structure the Front-End.
2. HTML - The Builder => ( Hypertext Markup Language) defines the context of the page, the images, links.
3. CSS - The Artist => ( Cascading Style Sheets) It gives style to HTML content. Defines the colours, the fonts and the
   positioning of content.
4. Javascript - the Wizard => pop up error messages, autocomplete.
5. Web Browsers( e.g.firefox, googlechrome) translate these three languages into the visual web page( UI- User
   Interface).
6. The Client runs the Front-End of the page and the Server the Back-End of the page.
7. HTTP( Hypertext Transfer Protocol) is an application-layer protocol for transmitting hypermedia documents, such as
   HTML. It was designed for communication between web browsers( Clients) and web Servers.
8. Request => Client to Server
9. Response => Server to Client
10. Alpine => Frond End, runs on the Client. It results immediate changes, without requesting the Server.
11. Livewire => Back End, the Client requests the Server and a response comes back to the Client.
12. Responsive Design (Tailwind css) => you can specify how your UI will be rendered depend on the size of a given screen.
13. Slug => is the last part of the url containing a unique string which identifies the resource being served by the web
    service, is a unique identifier for the resource
14. Laravel route model binding => provides a convenient way to automatically inject the model instances directly into
    your routes.( e.g. instead of injecting a user's ID, you can inject the entire User model instance that
    matches the given ID. e.g. Route::get('/ideas/{idea}', [IdeaController::class, 'show']);)

