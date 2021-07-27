rclone to rclone



settings->Secrets-> RCLONE_CONF #设置 RCLONE CONFIG

settings->Secrets -> S          #设置 S 源地址

settings->Secrets -> D          #设置 D 目的地

  rclone sync ${{ secrets.S}} ${{ secrets.D}} -P --bwlimit 20M --transfers 4

