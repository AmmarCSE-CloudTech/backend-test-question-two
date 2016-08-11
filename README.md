# backend-test-question-two
solution to question two

This solution depends on the [consistent-hashing](https://github.com/dakatsuka/node-consistent-hashing) library which already provides the majority of the functionality and tests.

I completed the solution by adding two methods to the plugins prototype, `addKey` and `getKey`, as well as writing their relevant test.

The way `addKey` was implemented is a bit hacky and had I more time, I would have implemented it correctly by separating *added* keys and *generated* keys andm making there structures and algorithms different.
