  1  ls -l /dev/sda{,[123]}

  2  lsblk --list

  3  cat /proc/diskstats

  4  cat /proc/devices

  5  dd if=/dev/zero of=./fs.img bs=1M count=10

  6  losetup --find --show ./fs.img

  7  sudo losetup --find --show ./fs.img

  8  losetup --list

  9  mkfs -t ext4 /dev/loop0

  10  sudo mkfs -t ext4 /dev/loop0

  11  -

  12  -

  13  sudo blkid /dev/loop0

  14  sudo mount /dev/loop0 /mnt

  15  mount | grep /mnt

  16  df -h /mnt

  17  df -hi /mnt

  18  sudo umount /dev/loop0

  19  tune2fs -l /dev/loop0

  20  sudo tune2fs -l /dev/loop0

  21  sudo losetup --detach /dev/loop0

  22  sudo losetup --list

  23  ls

  24  rm fs.img

  25  >lab6_history.txt

  26  history > lab6_history.txt
