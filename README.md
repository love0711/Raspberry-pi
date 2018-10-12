# Raspberry-pi

### Format SD Card to FAT32
`diskutil eraseDisk FAT32 RPI [SD Card BSD Name]`

### Unmount SD Card
`diskutil unmount [SD Card BSD Name]`

### 
`sudo dd bs=1m if=[Raspbian img path] of=[SD Card BSD Name]`
