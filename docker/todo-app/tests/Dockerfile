
FROM betrybe/puppetter:1.0
EXPOSE 3001
WORKDIR /app/tests
ADD node_modules.tar.gz /app/tests
COPY . /app/tests
ENTRYPOINT ["npm"]
CMD ["test"]
