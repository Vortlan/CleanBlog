## CleanBlog - 4. Bolum | Odev 10

# Clean Blog Projesi 4. Bölüm:

- index.ejs içerisinde /posts/<%= posts[i].\_id %> ile \_id bilgisini gönderelim
- app.js içerisinde GET metoduyla "/posts/:id" ile gönderilen "\_id" yi yakalayalım.
- tekil post bilgilerini post.ejs dosyasına gönderelim.
- post.ejs içerisine post.title, post.detail ve post.dateCreated bilgilerini gönderelim. (her bir post için ayrı image kullanmayacağız)
