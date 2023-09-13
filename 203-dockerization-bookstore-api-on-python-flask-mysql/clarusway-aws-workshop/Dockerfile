# MySQL Dockerfile
FROM mysql:latest

# Veritabanı kök şifresi
ENV MYSQL_ROOT_PASSWORD=mysecretpassword

# Veritabanı adı
ENV MYSQL_DATABASE=mydatabase

# İsteğe bağlı olarak karakter seti ve zaman dilimini ayarlayabilirsiniz
# ENV MYSQL_CHARSET=utf8mb4
# ENV MYSQL_COLLATION=utf8mb4_unicode_ci
# ENV TZ=UTC

# Portları dışarı açabilirsiniz (örneğin, 3306:3306)
 EXPOSE 3306

# İsteğe bağlı olarak başlatma komutlarını ekleyebilirsiniz
 CMD ["mysqld"]
