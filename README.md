# XB-C100
Repository for XB-C100 Firmware and Files

This repository is for the XB-C100 DMX / LED writer / programmer.

I am not the original creator of this firmware, but it has proven difficult to get these files as the current manufacturer of the XB-C100 is unknown.

Since it is an unbranded device, it's possible for it to become vaporware, so I'm putting the latest firmware files on Github for others who may need them.

If anyone else knows further information about this product, please reach out to me.  Thank you!



# Upgrading the firmware:

Apparently there are at least two generations (possibly more) of the XB-C100 device.  The latest generations that uses this firmware has a microSD card on the side of the touch screen.  To determine your model, you will have to unscrew the four machine screws holding the touchscreen to the rest of the case.



I'll include photos of what my model looks like.



Put the Touchscreen folder on the MicroSD card / TF Card, and insert into the screen, upgrade this first, then power cycle the device with the switch, and load the other firmware onto an SD card, and insert into the lower part of the controller.  It should update on boot.  Turn the power off, remove the SD card, turn back on, and now your firmware should display v3.5.



----- Change Log -----



Writemapper Version V3.5 Update:

1. Fixed an issue where the UCS8904 could not play with 1024 points.
2. Corrected the error in writing current parameters for the SM522 and SM16212 chips.
3. Added support for the MT1885 control protocol.
4. Added a "Unified Address" option in the UCS512K address writing interface.

Writemapper Version V3.4 Update:

1. Fixed data misalignment issues when controlling lights with the UCS9812.
2. Corrected incorrect current parameter data for the UCS512KH.

Writemapper Version V3.3 Update:

1. Added parameter writing functionality for the SM522 and SM18500 series.

Writemapper Version V3.2 Update:

1. Added parameter writing functionality for the GS8523, GS8524, and GS8526 chips.
2. Added support for the QS2633 and QS2639 control protocols.

Writemapper Version V3.0 Update:

1. Adapted to the new GS8525 parameter writing protocol.
2. Added UCS512-K-Self channel writing functionality.
3. Implemented hidden time display for the touchscreen.

Writemapper Version V2.9 Update:

1. Fixed issues with the "Unified Address" setting in the GS series address writing interface.
2. Fixed issues with the "Reset Address" function in the GS series.
3. Added address and parameter writing functionality for the GS8516B.
4. Added address and parameter writing functionality for the GS8525.

Writemapper Version V2.8 Update:

1. Fixed issues with the self-channel setting for the SM17500.
2. Optimized the DMX address detection functionality.
3. Added address and parameter writing functionality for the UCS512-C1.

Writemapper Version V2.6 Update:

1. Added support for upgrading via SD card.
2. Added playback and parameter writing functionality for the UCS7804.

Writemapper Version V2.4 Update:

1. Added address and parameter writing functionality for the UCS512-KH/KL.



写码器V3.5版本更新
1，修改UCS8904带载1024点不播放的问题
2，修改SM522、SM16212写电流错误的问题
3，新增MT1885控制协议
4，UCS512K写地址界面增加“统一地址”选项

写码器V3.4版本更新
1，修复UCS9812带载灯具数据错位的问题
2，修复UCS512KH写电流参数数据不正确的问题

写码器V3.3版本更新
1，新增SM522、SM18500系列写参数功能

写码器V3.2版本更新
1，新增GS8523、GS8524、GS8526芯片写参数功能
2，新增QS2633、QS2639控制协议

写码器V3.0版本更新
1，适配GS8525写参数新协议
2，新增UCS512-K-Self写自通道
3，触屏隐藏时间显示

写码器V2.9版本更新
1，修复GS系列写地址界面  统一地址 设置的问题
2，修复GS系列设置  地址清零  的问题
3，新增GS8516B写址写参数
4，新增GS8525写址写参数

写码器V2.8版本更新
1，修复 SM17500 设置自通道的问题
2，优化DMX测地址功能
3，新增 UCS512-C1写址写参数

写码器V2.6版本更新
1，新增SD卡升级功能
2，新增UCS7804播放和写参数

写码器V2.4版本更新
1，新增UCS512-KH/KL写址写参数





