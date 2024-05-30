#### 1.0.4 - 30th May 2024 ####

Reactive.Streams.TCK
   - Remove dependency to Reactive.Streams.Example.Unicast

#### 1.0.3 - 30th May 2024 ####

Reactive.Streams
   - Update target framework to .NET Standard 2.0

Reactive.Streams.TCK
   - Update target framework to .NET Standard 2.0
   - Bump NUnit version from 3.7.1 to 3.13.3
   - Add compatibility for NUnit 4
   - Remove code behavior dependency that are specific to NUnit 3.7.1

#### 1.0.2 - 07.04.2017 ####

Reactive.Streams
 - Stable release
 - Support for .Net Standard 1.0

Reactive.Streams.TCK
 - Stable release
 - Fix missing Cancel() in tests that don't consume the entire source #32
 - Skip §2.13 for value types #34
 - Fail NextN with the correct error message if timeout is reached #36
	
#### 1.0.0-RC1 - 04.07.2016 ####

Reactive.Streams 
 - Support for PCL Profile7
 - Removed non-generic IPublisher and ISubscriber interfaces.

Reactive.Streams.TCK
 - Initial release
