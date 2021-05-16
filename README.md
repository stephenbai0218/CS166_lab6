# CS166_lab6
先把txt sh sql 文件复制进去
source ./startPostgreSQL.sh
source ./createPostgreDB.sh
cp *.txt /tmp/$USER/myDB/data/
psql -h localhost -p $PGPORT $USER"_DB" <chapter5.sql
psql -h localhost -p $PGPORT $USER"_DB" 

开始写5个玩意


psql -h localhost -p $PGPORT $USER"_DB" <queries.sql
