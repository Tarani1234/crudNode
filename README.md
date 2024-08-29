## for get method 
app.get('/books', async (req, res) => {
  const books = await Book.find();
  res.send(books);
});
