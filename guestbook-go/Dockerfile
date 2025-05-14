FROM scratch
WORKDIR /app

COPY guestbook /app/guestbook
COPY ./public/index.html ./public/index.html
COPY ./public/script.js ./public/script.js
COPY ./public/style.css ./public/style.css

EXPOSE 3000
CMD ["/app/guestbook"]
