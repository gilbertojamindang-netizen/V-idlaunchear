# Horizon compatibility decision

The uploaded Horizon Android repository is a separate Rust-native Minecraft implementation. Its supplied project metadata/documentation identifies a Minecraft 26.3 target. It is not a drop-in renderer or engine library for the Zalith/Pojav Minecraft Java 1.21.11 pipeline.

For the requested 1.21.11 release, keep Horizon out of the game launch path. Revisit only individual reusable utilities after checking their APIs, licenses, native ABI, Android minimum SDK, and dependency graph. Do not mix native libraries blindly.
