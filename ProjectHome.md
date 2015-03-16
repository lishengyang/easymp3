an easy mp3 based on atmega8 and vs1003b

avr mega8l mcu based ,c languague  source codes here for downloading
and also the pcb board original protel type documents for pcb making.

随着数码技术在生活中的广泛应用，各种消费电子产品之间的数据交换变得非常频繁，而家庭音响也逐渐脱离磁带，CD,VCD等传统介质，而代之以存储卡，U盘，硬盘或网络硬盘。基于成本和内容更新方便与否的考虑，来设计一款以SD卡为介质的MP3音响。
本论文主要是设计一款具有优秀音质且成本低廉的音响音源，文件采用mp3格式，考虑到此种网络音乐格式的普遍性。SD卡读取方式为spi模式，充分利用单片机支持的总线结构，MP3解码技术，fat文件系统，实现完整的mp3的播放。
电路架构采用atmel公司的8位单片机atmega8L作为主控芯片，与vlsi公司的解码芯片vs1003b，将sd卡内的mp3文件解码输出为音频信号，通过音响输出。经实做结果显示此架构确能提供低失真度，低功耗的音质。
若加入性能更优秀的功放模块提高其输出功率，此产品可以改造成家庭hifi音响的一部分，或者加入无线RF传输功能，则可以实现无线音响的功能，使得在屋内各处都可收听到音乐，可应用于无线数字广播系统。

