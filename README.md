# SuperCHIP V1.0 (Original) High Resolution Font Test

This test is designed to check if the interpreter is properly supporting SuperCHIP 1.0 (Original) in regards to loading fonts (through the `FX29` opcode), primarily high resolution.  That is because SuperCHIP V1.0 loads high resolution fonts differently from SuperCHIP V1.1 and other extensions.

|Status |Description |
|-------|------------|
|`CHIP-8 Found!`|This status will display if it mimics the original COSMAC VIP CHIP-8 font handling (by ANDing the least significant nibble).|
|`SCHIP 1.0 Found!`|This status will display if the `FX29` opcode does support SuperCHIP V1.0 (Original)-like behavior for font loading.|
|`X`|This status will only display if the interpreter does not handle font loading properly (very likely not ANDing the least significant nibble).|
