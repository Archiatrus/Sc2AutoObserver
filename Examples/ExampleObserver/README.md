### Example for the use of the Sc2AutoObserver to simulate an observer for a replay

How to use:
To build this example the paths of the libs and includes of the sc2api have to be set. After building the executable make the following call in the command console:
`ExampleObserver.exe --Path "<Path to a single SC2 replay or directory with replay files>" --Speed <Replay speed>`

### Known bug:
* Only the perspective of one player. The protobuff request to go to everyone perspective is included, but it is not yet implemented on the protobuff level. That means once Blizzard updates this feature it should work automatically for the autoObserver.