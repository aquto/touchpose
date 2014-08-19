# cordova-plugin-touchpose

To install this plugin, follow the [Command-line Interface Guide](http://cordova.apache.org/docs/en/edge/guide_cli_index.md.html#The%20Command-line%20Interface).

If you are not using the Cordova Command-line Interface, follow [Using Plugman to Manage Plugins](http://cordova.apache.org/docs/en/edge/guide_plugin_ref_plugman.md.html).

This plugin adds the touchpose application files to the project, you still need to modify the main.m like below:

    #import <UIKit/UIKit.h>
    #import "QTouchposeApplication.h"

    int main(int argc, char *argv[]) {
        
      @autoreleasepool {
        int retVal = UIApplicationMain(argc, argv, NSStringFromClass([QTouchposeApplication class]), @"AppDelegate");
        return retVal;
      }
        
    }


## License ##

The MIT License (MIT)

Copyright (c) 2013 Joshua Runge, Aquto

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
