Bot for Runescape NXT client I made long time ago. Uses yara patterns and code analysis using capstone to find reliably important functions across builds (may require some updates time to time). Provides protobuf API using gRPC for interacting with the game.

Shouldn't be expected to work outside the box and contains a lot of absolute paths relative to my machine.

Does not provide path traversal functionality.

Note: Some function names related to rs3 game functionality maybe incorrect (or vague), because they were mostly decided empirically based on what kind of data they processed.
