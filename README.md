# Ruby-on-Rails-related Workspaces as code configuration

This WAC file for Coder for Docker - uses Coder Technologies' Workspaces as code innovation to automate and configure-as-code the parameters of a data science-related workspace ( aka development environment )

Press the button to authenticate into a Coder instance and execute the coder.yaml

###### https://coder.com/docs/workspaces/workspaces-as-code

###### localhost:7080
[![Open in Coder](https://cdn.coder.com/embed-button.svg)](http://localhost:7080/wac/build?template_oauth_service=github&template_url=git@github.com:mtm20176/c4d_ruby_wac.git&template_ref=main&template_filepath=.coder/coder.yaml)

###### Notes / To run this app after cloning, we recommend:

* builds a cloud container using specified compute resources

* includes Coder's code-server open-source project to run VS Code in a browser

* installs VS Code extensions for Ruby development

* clones several GitHub repositories

* builds dependencies in particular Ruby gems with Bundler

* For rubyonrails repo, API call #1 to demo in a browser: http://(your app host name)/api/get_posts_count.json

* For rubyonrails repo, API call #2 to demo in a browser: http://(your app host name)/api/get_posts.json?term=

* For debugging with Ruby VS Code extension, start debugger command: rdebug-ide --host 0.0.0.0 --port 1234 --dispatcher-port 1234 -- bin/rails s
