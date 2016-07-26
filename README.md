# Ruby on Windows
Documentation for running Ruby scripts on Windows machines

### Installing Ruby on Windows
1. Download Ruby using [RubyInstaller](http://rubyinstaller.org/downloads/).
2. In the Installation Destination and Optional Tasks, check off the boxes that say "Add Ruby executibles to your PATH" and "Associate .rb and .rbw files with this Ruby installation".

### Running Ruby Scripts on Windows
1. Open command prompt and run the command `ruby --version` to verify correct installation.
2. Access the directory containing the Ruby script.
3. Run the Ruby script by using the command `ruby filename.rb`.

##### Troubleshooting
- Make sure all gems have been correctly installed (if any errors contain "require: cannot load such file", chances are running `gem install file_that_cannot_be_required` will resolve that issue.
