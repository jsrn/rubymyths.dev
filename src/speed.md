---
layout: default
---

## "Ruby is slow!"

### "Slow" isn't useful

First off, a concession: Yes, Ruby is slower than many languages on many benchmarks. **However.** "Slow" is a useless descriptor if you don't have a "fast enough."

Allow me to strain an analogy. If you're a driver, I'd bet that whatever car you drive isn't as fast as what they take on the F1 track. There's a good chance that you still consider your car _fast enough_. If you do have a super fast car, you might brag to your friends about how it does zero to sixty in 0.036 seconds, but 99% of the time you're never going above the posted speed limit.

At some point you start asking more relevant questions like how many cupholders it has.


### Did you know...

... that contributors to the Ruby language have made [excellent progress](https://codefol.io/posts/is-ruby-3-actually-three-times-faster/) on Ruby 3x3, the goal that Ruby 3 should be _three times_ faster than Ruby 2?

... that there are Ruby implementations like [JRuby](https://www.jruby.org/) and [TruffleRuby](https://www.graalvm.org/ruby/) built for concurrency and speed?

... that Ruby's got a snazzy new [JIT compiler](https://github.com/ruby/ruby/blob/master/doc/yjit/yjit.md) that's leading to some [pretty nice gains](https://shopify.engineering/yjit-just-in-time-compiler-cruby)?

... that Ruby 3 introduced [Ractors](https://ruby-doc.org/core-3.0.0/Ractor.html), a handy implementation of the Actor Model for concurrency?
