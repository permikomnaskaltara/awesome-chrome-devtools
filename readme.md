# awesome-chrome-devtools

_Awesome tooling and resources in the Chrome DevTools ecosystem_

## DevTools as an IDE
* [Chrome DevTools App](https://github.com/auchenberg/chrome-devtools-app) standalone devtools app which can inspect various targets.
* [DevTools Remote](https://devtoolsremote.com/) Remotely debug someone else's browser via Chrome DevTools.

## DevTools as a lib
* [chrome-devtools-frontend on NPM](https://www.npmjs.com/package/chrome-devtools-frontend)
* [chrome-timeline-model](https://www.npmjs.com/package/devtools-timeline-model)

## Chrome Debugging Protocol
* [Debugging Protocol Viewer](https://chromedevtools.github.io/debugger-protocol-viewer/) easy browsable UI for exploring the protocol's domains, methods and events
* [chrome-remote-interface](https://github.com/cyrus-and/chrome-remote-interface) recommended node API for the protocol. [This module](https://github.com/DickvdBrink/chrome-debug-protocol) offers an TypeScript-friendly alternative
* [Remote Debug Gateway](https://github.com/RemoteDebug/remotedebug-gateway) allows you to connect a client to multiple browsers at once.
* [Remote Debug Firefox adapter](https://github.com/RemoteDebug/remotedebug-firefox-adapter) translates Firefox's devtools protocol to the CDP
* [ios-webkit-debug-proxy](https://github.com/google/ios-webkit-debug-proxy) exposes Mobile Safari & UIWebView instances via the CDP.
* [devtools-compat-proxy](https://github.com/artygus/devtools-compat-proxy) young effort to translate modern Safari debugging protocol to modern CDP
* [crmux](https://github.com/sidorares/crmux) multiplexer to handle multiple clients

## Network Inspection
* [betwixt](https://github.com/kdzwinel/betwixt) : system level network proxy, providing inspection via Network panel

## CPU profile
* [JSCLegacyProfiler/json2trace](https://github.com/facebook/react-native/blob/master/JSCLegacyProfiler/json2trace) converts Safari's JavaScriptCore profiler output into `.cpuprofile`
* [call-trace](https://github.com/brendankenny/call-trace) can apply instrumentation to your JS. After evaluating, it can then generate `.cpuprofile` files with either the full instrumented execution trace with execution time or call counts.
* [cpuprofilify](https://github.com/thlorenz/cpuprofilify) converts output of various profiling/sampling tools to the `.cpuprofile` format

# Tools that debug Chrome over the protocol
* [Showcase Protocol Clients](https://developer.chrome.com/devtools/docs/debugging-clients) lists many, like Brackets, Vim, LightTable, Sublime, tec.


# Tools that generate `cpuprofile` output
* [Wishbone python framework](http://wishbone.readthedocs.org/en/develop/miscellaneous.html#profiling)