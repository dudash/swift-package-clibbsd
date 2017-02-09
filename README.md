# swift-package-clibbsd
Simple wrapper around the C Library BSD for use with Swift Package Manager on Linux

Note: you will need to `apt-get install libbsd-dev`

You can reference this from your Package.swift file in the dependencies section as follows:
<pre>
dependencies: [
   .Package(url:  "https://github.com/dudash/swift-package-clibbsd.git", majorVersion: 1)
]
</pre>
