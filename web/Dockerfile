FROM nginx:1.25.3

# デフォルトの設定ファイルを削除
RUN rm -f /etc/nginx/conf.d/*

# 独自の設定ファイルを配置
COPY nginx.conf /etc/nginx/conf.d/custom.conf