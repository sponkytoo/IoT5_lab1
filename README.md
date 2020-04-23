# IoT5_lab1
IoT5 Lab 1 Hands On



@ECHO OFF
set H3_PATH="https://github.com/Microchip-MPLAB-Harmony"
mkdir h3
cd h3
git clone -b "v3.5.1"               %H3_PATH%/net.git
git clone -b "v3.5.2"               %H3_PATH%/core.git
git clone -b "v3.5.2"               %H3_PATH%/csp.git
git clone -b "v3.5.0"               %H3_PATH%/bsp.git
git clone -b "v3.5.0"               %H3_PATH%/dev_packs.git
git clone -b "v3.4.1"               %H3_PATH%/crypto.git
git clone -b "v4.1.0-stable"        https://github.com/wolfSSL/wolfssl.git
git clone -b "v1.2"                 https://github.com/wolfSSL/wolfMQTT.git
git clone -b "10.2.0"               https://github.com/ARM-software/CMSIS-FreeRTOS.git
git clone -b "v3.3.5"               %H3_PATH%/mhc.git
git clone -b "v1.3.1"               %H3_PATH%/contentmanager.git
git clone -b "v3.1.1"               https://github.com/Microchip-MPLAB-Harmony/wireless.git
cd ..
git clone https://github.com/sponkytoo/IoT5_lab1.git


