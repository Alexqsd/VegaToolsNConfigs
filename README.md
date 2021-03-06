# VegaToolsNConfigs
AMD Vega GPU tools and configuration file(s) for Monero(XMR) mining.


# NOTE:
This guide will work with most cryptonight V7 coins at Windows level hash rate(s).  Most cryptonight V8 miners will not work with 18.30 driver.  Please use cast-xmr for the time being.  The hash rate is around 1250 H/s for XMR.  If you want to use xmrig-amd or xmr-stak, use ROCm 1.9.1+.  UPDATE: The cast-xmr with Vega 56/64/FE will get you 1600/1870/1960 H/s on --intensity=10/10/9(default is 7).  All miners(cast-xmr/xmrig-amd/xmr-stak) have the very close hash rates on ALL VEGA GPUs under amdgpu-pro 18.10/18.30.  ROCm 1.9.1 is still stuck with lower hash rates.

VegaUbuntuGuide - How to manually setup Vega mining in Ubuntu for CryptoNight V7.

VegaUbuntuGuide4CryptoNightV8 - How to manually setup Vega mining in Ubuntu for CryptoNight V8 with ROCm driver.

VegaUbuntuQuickGuideForCNv2 - How to manually setup Vega mining in Ubuntu for CryptoNight V8 with AMD drivers for "Experts". 

VegaUbuntuGuideForCNv2- How to manually setup Vega mining in Ubuntu for CryptoNight V8 with AMD drivers.


Working Ubuntu Versions:

Ubuntu MATE 18.04.1

Ubuntu MATE 16.04.5


VegaUbuntuGuideWithAutoTools - How to setup Vega mining in Ubuntu with 90% automation.  Essentially the same as VegaUbuntuGuide but after a few manual downloads, run the scripts to setup.

OptimalRunningSequencesForVegas - Running sequences for maximum hash rate.

History - Addition(s) and changes by date.

TestedHarware - Limited hardware list working or not.

config folder - contains gpu and mem clock settings.

config/PPTDIR folder - contains
1. PPT binary files for Vega 56/64/FE.
2. PPT hex table in text format to generate binary PPT file.
3. SoftPPT-1.0.0.jar to convert hex table to binary PPT file.
4. SoftPPTProj.tgz(The maven java project to make SoftPPT-1.0.0.jar program).

tools folder - contains shell scripts for fan speed, overclocking, monitoring and setting PPT.

tools/rigmonitor folder - contains rig monitoring scripts using passwordless ssh method.

Binary file checksums:
1.   b959ad1ffd296a8c5c75d1eb9e11e467  V56PPT
2.   4c9fc25157f392e9c94ab1536847b7c0  V64PPT
3.   ed13313360a2a4306e11a62afd111ace  V64V8PPT
4.   e30d9cd42cfe2190e263cd7f04aaef6f  SoftPPT-1.0.0.jar

LIMITATIONS

Four Vega GPUs per motherboard for XMR mining.  Risers and extenders working with some motherboards.

The limitations have been upgraded to 6 GPUs with risers.

The limitations have been upgraded to 8 GPUs with Colorful's motherboard without risers.


Tested coins:

    CryptoNightV7(CNV1):

        Monero(XMR)(Updated to CNV2)

        GRAFT

    CryptoNightV8(CNV2):

        Monero(XMR)


Contact(s)

xmrminer01102018@gmail.com

Glossary
1. PPT - Soft Power Play Table
2. Ubuntu - Linux OS
