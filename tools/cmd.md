#Usefull cmd for this minecraft server

sftp -P port username@hostname
sftp -P 2022 rpykt77s.fb2a59d3@game23-dc02.ouiheberg.com
rpykt77s.fb2a59d3@game23-dc02.ouiheberg.com

lcmd to launch cmd in local
ls & cd work as usuel
rm -r = rmdir
put -transfer local file

rm plugins/dynmap/configuration.txt
put plugins/dynmap/configuration.txt plugins/dynmap/
put plugins/*.jar plugins/


winscp "EarthCube ouiheberge"

winscp.exe "EarthCube ouiheberge" /synchronize "C:\Users\lili5\git\EarthCube\server\" "/" both -delete -preview
git add server/*;git commit -m "auto update server file to git";git push

winscp.com /script=script.winscp
git add server/*;git commit -m "auto update server file to git";git push
