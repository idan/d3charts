# d3charts

A higher-level charting library built on top of [d3](http://mbostock.github.com/d3).

D3 is really quite awesome. It is a low-level toolkit of primitives for visualizing data in modern browsers, abstracting away a lot of the common gruntwork of any visualization. I like to think of d3 as the web’s “native” visualization toolkit, since it isn’t a very abstract abstraction: d3 produces SVG and maniupulates markup in your browser, not some intermediate representation. This makes things like interactivity possible/easier.

### So why a charting library?

With great power comes great headache. D3 provides the primitives you need to build anything, but constructing the most basic chart out of primitives is not a one-liner activity. Even if you’re familiar with graphics programming, finding your way around d3 can be a little intimidating at first. Sometimes you just want a basic chart of something, and you’d like the option of later adding on bells and whistles. D3charts aims to supply that, as well as serving as a good library of examples to learn/steal from if you want to implement your own charts.

### Steal?

All good, komrade! We are being supply code under license “BSD” of three clause. Use and abuse required immediately now. Making sure to read `LICENSE` file.

### Pull requests?

Hell yes, please.

### Styling charts?

These plugins create charts with the bare minimum of styling applied. Charts are just SVG, you can (and should!) style them with CSS like any other markup. The `examples` directory provides some, er, examples.

### Preview?

Sure.

* [Histogram](http://bl.ocks.org/1564489)
* more coming soon…

