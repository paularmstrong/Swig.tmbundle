## About

This is a TextMate bundle for [Swig](http://paularmstrong.github.com/swig), a template engine for Node.js.

## Installation

    git clone git@github.com:paularmstrong/Swig.tmbundle.git && open Swig.tmbundle

## Included

### Language Definition

Swig assumes it is a subset of the HTML language definition. All HTML-based commands and preferences are extended via the Swig bundle.

This bundle adds support for tag-folding, Swig comments, and smart typing pairs.

### Tags

All tags support tab-completion

    block⇥

    {% block ${1:blockname} %}
        $0
    {% endblock %}

### Filters

Filters are supported under the <kbd>⌘\</kbd> keyboard command. Hit <kbd>⌘\</kbd> to get a list of built-in filters.

## License

Copyright (c) 2011 Paul Armstrong, Paul Armstrong Designs

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
