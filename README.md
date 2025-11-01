# Horde Build Mirror
Mirror of my Horde build project to make the codebase easier to find. Since this build system was originally built for [Shadow Engine](https://github.com/77Z/Shadow-Native), it currently lives there. With that being said, it can exist independently and is used in my other projects now.

# Where can I find the real one?

## [Here](https://github.com/77Z/Shadow-Native/tree/master/scripts/Horde)

# What's this project all about?

It's a build file generator for the Ninja build system. It takes in a build.json5 ([see example here]()) file that specifies how a C/C++ project should be built, and Horde will generate .ninja build files that can be used to compile your code!

It's written in TypeScript and runs on the Deno JS runtime.
