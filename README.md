MMTabBarView (beta)
============

A Mac OS X tab bar view that works on 10.6-10.8 with Xcode 4.x.<br>
MMTabBarView is a modernized and view based re-write of PSMTabBarControl, <br>
which can be found here: https://github.com/dorianj/PSMTabBarControl<br>
Though MMTabBarView's API is quite similar, it is not a drop-in replacement for PSMTabBarControl:
Due to conceptual and structural changes, the MMTabBarViewDelegate protocol is somewhat different.

If you want to support this project, there are various ways in which you could do this:<br>

<ul>
<li>Send me a pull request.</li>
<li>Review it on your site or blog.</li>
<li>Make a donation via PayPal following the link below (credit cards etc. accepted too).</li>
</ul>
        
Donating via PayPal is as easy as clicking the donate button on this page:
http://mimo42.github.com/MMTabBarView/

If you make any improvements, please submit them as pull requests.

## State

The project is still in a beta state. Some Styles need to be adjusted.
There is still some old code that should be replaced.

## Building

To, build, simply open default.xcworkspace, choose MMTabBarView Demo scheme and run.
The workspace contains two projects, the MMTabBarView framework and the Demo application.

## Installing
Add the .framework bundle to your xcode project, and add it to the Linked Frameworks and Libraries (under Target -> Summary). Next, under Target -> Build Phases, Add a new build phase that copies it to the Frameworks directory of your app. (Add Build Phase > Copy Files. Destination: Frameworks)

## Copying
Some components and lines originally were created by Positive Spin Media. The original is BSD licensed.<br> 
See: http://www.positivespinmedia.com/dev/PSMTabBarControl.html License<br>
The re-write is also BSD licensed.<br>
Since 2005 there have been lots of commits by various contributors.<br>
Thanks to the guys recently improved PSMTabBarControl and inspired me to finally do the re-write!

## License
Copyright © 2005, Positive Spin Media. All rights reserved.<br>
Copyright © 2012, Michael Monscheuer. All rights reserved.<br>

<hr>
Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

<pre><code>* Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.
* Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.
* Neither the name of Positive Spin Media nor the names of its contributors may be used to endorse or promote products derived from this software without specific prior written permission.
</code></pre>

<p>THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT OWNER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.</p>