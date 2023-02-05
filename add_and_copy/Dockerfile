FROM ubuntu

RUN mkdir hello
WORKDIR /hello

# tar ファイルを展開
ADD ./tar_dir/hello.tar /hello/ 
# Dockerfile と同階層に置いている for_copy ファイルをコンテナ内の hello ディレクトリに追加
COPY ./for_copy /hello/
