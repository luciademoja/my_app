# my_app

What are these gems and what do they do?
Gems are Ruby libraries that integrate and enhance the basic commands allowing to perform more advanced tasks, like the following:

@ gem 'capybara' => simulates the user/website interaction and has synchronization features that make it wait for the content to appear on the webpage before acting. It's been included in this project in order to allow the developer to test the web application on the user perspective.

@ gem 'launchy' => it's a gem that allows to overlook on which platform a developer is operating, providing a common approach that makes one able to launch external applications using programs written in Ruby. Due to the multiplatform nature of this course, it is appropriate to add this gem to my_app in order to make other gems functional on any platform.

@ gem 'rspec' => Rspec is a framework that allows Behavior Driven Development. It is useful in order to test the application.

@ gem 'shotgun' => this gem restarts an application every time there is a request. It saves time to the developer restarting the application at every request instead of waiting for the manual restart. Shotgun is not available for platforms like Windows and JRuby so the launchy gem is necessary for it to work in those platforms.

@ gem 'rack-test' => it is a testing application program interface for apps that use Rack as webserver interface. Since my_app is going to be a web application and uses Rack, this gem is useful to set up the testing environment.

Minimum requirements for an HTML 5 page

It is good practice to start the document declaring <!DOCTYPE html> even though this tag is not necessary for the document itself to be readable.
A necessary tag is the <html></html>, which indicates where the html code starts and ends.
In order to be able to format the page, a <head></head> and <body></body> are necessary. The <head> tag should contain the title of the web page, together with links to the stylesheets and all the meta attributes that contribute in encoding the characters. Also links to scripts that were written somewhere else outside the document should be contained in the head section.
The <body> tag contains everything else, including the <script></script> tag in case the developer decides to write it inside the same document.
It is also good practice to declare the language used adding the lang attribute to the <head> opening tag.

When we speak about assets, what do we mean?

The definition of asset indicates something/someone that can be useful in present or future matters due to its attributes or skills (like reusability). My guess is that in this case, an asset is an object or a piece of code that can be written/created once and used multiple times in different contexts.
