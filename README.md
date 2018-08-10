# Netscope

A web-based tool for visualizing neural network topologies. It currently supports UC Berkeley's [Caffe framework](https://github.com/bvlc/caffe).

### Documentation
- [The Quick Start Guide](http://leeesangwon.github.io/netscope/quickstart.html)

### Demo
- [Visualization of the Deep Convolutional Neural Network "AlexNet"](http://leeesangwon.github.io/netscope/#/preset/alexnet)

### License

Released under the MIT license.
All included network models provided under their respective licenses.

---

## How to edit and build code (windows)

1. clone this repo
2. install node.js
3. run Node.js command prompt
4. move to netscope folder
5. run

    ```cmd
    npm install
    npm install browserify -g
    ```

6. edit coffeescript code
7. run

    ```cmd
    browserify -t coffeeify src/netscope.coffee -o assets/js/netscope.js
    ```

8. push
