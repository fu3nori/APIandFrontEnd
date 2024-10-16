# ./php/Dockerfile
FROM php:latest

# 必要なパッケージをインストール
RUN apt-get update && apt-get install -y \
    unzip \
    git \
    curl

# Composerをインストール
RUN curl -sS https://getcomposer.org/installer | php -- --install-dir=/usr/bin --filename=composer

# 作業ディレクトリを設定
WORKDIR /var/www/html

# ポート80を公開
EXPOSE 80

# PHPビルトインサーバーを起動
CMD ["php", "-S", "0.0.0.0:80", "-t", "/var/www/html"]
