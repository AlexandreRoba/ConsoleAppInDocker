FROM microsoft/aspnet:1.0.0-rc1-update1

COPY . /helloworld
WORKDIR /helloworld
RUN ["dnu", "restore"]

ENTRYPOINT ["dnx","helloworld"]