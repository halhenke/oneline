# What is this?

Inspired by discussion debate around "extreme modularity" and the creation/use of packages that might consist of only a single line of code. See [here](https://github.com/sindresorhus/ama/issues/10)

Basically the idea is that by bundling these micro-packages into a lodash style utility library they will be more discoverable to package consumers i.e. you might not even think to look for a module that checks if a number is `-0` on npm but if you know theres a library that might contain such code you'd be more likely to check there. And over time you might have more of an idea of what already already exists. All modules will be available as individual npm packages, again a la lodash.

I'm not sure if this type of programming will be particularly useful or will lead to the downfall of modern civilization but hopefully a library like this might mitigate some of the potential downsides of this type of fine grained modularity while maintaining the theoretical advantages.

# Placeholder for now

Because I only thought of this half an hour ago...
