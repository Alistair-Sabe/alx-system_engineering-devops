su -> switch user

whoami -> show current user

groups -> groups current user belongs to

sudo chown _user_ _file_ -> change file ownership

touch _file_ -> create empty file

chmod u+x -> give user executable permissions

chmod ug+x,o=r -> giver owner and group execute permissions but read permission for others

chmod ugo+x -> giver owner,group and others execute permissions to the file

chmod 007 _file_ -> permissions only given to other users

chmod 753 _file_ -> change permission 3=no write for other users

chmod --reference=_RFfile_ _file_ -> clone permission from one file to another

chmod -R +X . -> give execute permission to subdirectories

mkdir -m 751 _mydir_ -> create directory with permissions

chown :school _file_ -> change group owner

chown -R _user_:_group_ . -> change owner and group owner

chown -h _owner_:_group_ -> change owner and group for symbolic link file

chown --from=_oldOwner_ _newOwner_ _fileName_

telnet towel.blinkenlights.nl -> play starWars episode
