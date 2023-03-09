# re-frame-utils

> Re-frame extensions

Pipo Saúde's fork of the currently unmantained [re-frame-utils](https://github.com/den1k/re-frame-utils).

## Releases and Dependency Information

Add it to `deps.edn` (check for latest release tag and sha)

``` clojure
io.github.piposaude/re-frame-utils {:git/tag "0.2.0"
                                    :git/sha "05f5144481d04856520fc2cd672d6bb9c798fe48"}
```


## Dependencies and Compatibility

Tested against `re-frame 1.3.0` and `clojurescript 1.10.773`.



## Utils



### Cofx



#### [Inject](./src/com/piposaude/re_frame/cofx/inject.cljc)

Inject a subscription in an event handler.



### Fx



#### [Track](./src/com/piposaude/re_frame/fx/track.cljc)

Dynamically dispatch events when subscriptions update.



## License

Copyright © 2017 Vimsical

MIT License
