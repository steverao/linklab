# LinkLab-An IoT teaching platform

物联网应用的一个特点在于设备的异构性，一个物联网应用往往包含多种不同类型的设备。设备的异构性给应用的开发带来了两个主要问题。一是学习成本高，针对不同的设备，开发者需要搭建不同的开发环境，学习不同的开发语言，导致了物联网设备端开发学习成本的提高；二是设备选择，应用测试困难。面对多种多样的设备，如何选择最合适特定应用的设备对于不熟悉物联网硬件的开发者来说有很大困难。

针对第一个问题，本系统通过一套统一编程语言和云端编译技术，屏蔽了不同硬件在开发上的差异，降低了物联网设备端应用开发的难度。针对第二个问题，阿里巴巴推出了物联网在线开发板/设备平台 （uDevice Center），将设备搬到线上，开发者无需购买，即可远程使用多种多样的物联网设备，降低了设备选择、应用测试的难度。

用户在linklab系统中进行物联网实验时，仅需采用统一的编程语言编写所需开发的物联网应用程序，该平台将对代码进行云端编译，烧写入uDevice Center中的特定硬件当中，只要写代码就可轻松完成物联网应用的开发。linklab让传统物联网应用开发变得跟软件开发一样简单