# インストール  

## fdisk  
インストール領域とswap領域作成。  

## mkfs.ext4
インストール領域にファイルシステム作成。    

## mkswap  
swap領域初期化。

## mount  
インストール領域マウントする。

## mkdir  
setup-chrootコマンドを読んで、必要なディレクトリをインストール領域に作成する。

## ファームウェアをコピー  
/lib/firmware/* を/mnt/lib/firmware/にコピーする。

## setup  
ファイルをインストールする。

## setup-chroot  
ルートが/mntになる。

## passwd  
rootのパスワード設定

## 編集  
/etc/fstab
/etc/lilo.conf
/etc/rc.conf

## カーネルコンパイル  
スリムにしようとすると地獄。今動くカーネルはバックアップとって、lilo.confに記述しておくこと。

## wifi設定  
/proc/net/wirelessがあるか？

## ports -u  

## pkgmk -d
もしFootprintがとかSignetureがどうとかでMakeエラーになったら、ls -a で見えるファイル消してmakeすること。  


