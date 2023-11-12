# Wired Frameworks

WiredFrameworks is an Xcode project that regroups library and framework targets involved in the Wired 2.5 implementation on OSX.

See this [page](http://www.read-write.fr/wired/wiki) to find more documentation about Wired

## How to use it

		brew install cocoapods svn
  		git clone https://github.com/ProfDrLuigi/WiredFrameworks
		cd WiredFrameworks/
		git clone https://github.com/ProfDrLuigi/libwired
  		pod install
		cp -r Pods/RegexKitLite WiredFoundation/.
				
## Authors

Most of the code distributed here was originally written by Axel Andersson at Zanka Software. My contribution here is mainly related to iOS support and bug fixing.

This code is distributed under BSD license, and it is free for personal or commercial use.
		
- Copyright (c) 2003-2009 Axel Andersson, All rights reserved.
- Copyright (c) 2011-2013 Rafaël Warnault, All rights reserved.
		
Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:
		
Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer. Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.
		
THIS SOFTWARE IS PROVIDED BY THE AUTHOR ``AS IS'' AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

