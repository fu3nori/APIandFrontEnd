# 使用方法
それぞれ使用する言語に対応するディレクトリにソースコードを置いて下さい。 

# 利用ポート
phpmyadmin		4040  
php				4060  
bitnami/rails	8080  
node			3000  
mysql			3306  
jitesoft/go		4700  

# アクセス
http://localhost:4040 phpmyadmin    
http://localhost:4060 php  
http://localhost:8080 rails  
http://localhost:3000 node  
http://localhost:4700 go  

# mysqlのデフォルトパスワード
grepして書き直してください  
root:19810402qpdl

# 起動 
cd $docker-compose.ymlが存在するディレクトリ  
docker-compose up -d  
cd node  
cd react-myapp  
npm start  

# 終了
docker-compose down