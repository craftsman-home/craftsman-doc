# Setup Environment(ruby for windows)

## Setup environment step.
### Step 1 : Install ruby

You can downloads new verison for http://rubyinstaller.org/downloads/

![ruby-install](img/ruby-install.png)

### Step 2 : Install devkit

get the file [here](http://rubyinstaller.org/downloads/)

run the .exe file to unzip files into c:\DevKit

open your command line and type：
```code
> cd c:\DevKit
> ruby dk.rb init
> ruby dk.rb install --force
```

### Step 3 : Install bundler
open your command line and type：
```code
> gem install bundler
```

## Configure your DEV IDE（Use VS Code）
### Step 1 : Download & Install VS Code

You can downloads new verison for https://code.visualstudio.com/.

There are many extensions for Ruby.

![vscode-extensions](img/vscode-extenions.png)

### Step 2 : Install Ruby Extensions

Open your VS Code and click 'Extensions' button.

type 'ruby' in your search text box. install the first one.

> This extension provides rich Ruby language and debugging support for VS Code. you can get more information [here](https://github.com/rubyide/vscode-ruby)

![ruby-extensions](img/ruby-extensions.png)
