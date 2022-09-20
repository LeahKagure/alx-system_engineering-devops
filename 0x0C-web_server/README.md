0. **Transfer a file to your server** - Write a Bash script that transfers a file from our client to a server
1. **Install nginx web server** - Web servers are the piece of software generating and serving and serving HTML pages, let's install one!
2. **Setup a domain name** - Provide a domain name in your answer file
3. **Redirection** - Configure your Nginx server so that `/redirect_me` is redirecting to another page
4. **Not found page 404** - Configure your Nginx server to have custom 404 page that contains the string `Ceci n'est pas une page`
5. **Install Nginx web server (w/Puppet)** - Install and configure an Nginx server using Puppet instead of Bash. Include resources in your manifest to perform a 301 redirect when querying */redirect_me*
