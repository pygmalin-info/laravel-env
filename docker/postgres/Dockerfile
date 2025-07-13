FROM postgres:bookworm

# タイムゾーンの設定
ENV TZ=Asia/Tokyo

# ARGを使用してビルド時に環境変数を受け取る
ARG POSTGRES_DB \
    POSTGRES_USER \
    POSTGRES_PASSWORD

# ENVを使用してコンテナ実行時に環境変数を設定
ENV POSTGRES_DB=${POSTGRES_DB} \
    POSTGRES_USER=${POSTGRES_USER} \
    POSTGRES_PASSWORD=${POSTGRES_PASSWORD}
