# iOS-Learning


I'm writing these dmeos to improves my iOS skills. 
These demos are cover all aspects of iOS development, like Function Time Profiler, Quickly Debugging, Static Analysis, Crash Monitor, Log Catch, etc.

Following list is that i will implement in the future.

- [ ] Function Time Profiler. The Profiler can records time lenght of any function invoke, then we can anlysis these infos to optimize load velocity of our applications. We have two ways to realize it.
  - [ ] We regularly pull stack info of main thread. 
  - [ ] We hook the `msg_send` method, All Objective-C method calls will trigger the `msg_send` method.

- [ ] Improves the efficiency of debugging.
