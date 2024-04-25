Part 1:
code:
![Image](code3.png)
![Image](code4.png)
using:
![Image](using3.png)
Question:
1. It called the methods `handleRequest(URI url)`, `display()`and `getPath()`.They are called to get the path and query, then display the chat history.
2. The relevant arguments of `handleRequest(URI url)` is `url`, It is where the path and query from. And a relevant field is `history` which is the list of the chat history.
3. Before the request, the relevant field `history` was empty, and afterward it became "jpolitz:Hello". The port number became 8889.

![Image](using4.png)
Question:
1. Same as before, the methods `handleRequest(URI url)`, `display()`and `getPath()` were called. They are called to get the path and query, then display the chat history.
2. Same as before, The relevant arguments of `handleRequest(URI url)` is `url`, It is where the path and query from. And a relevant field is `history` which is the list of the chat history.
3. Before the request, the relevant field `history` was "jpolitz:Hello", and afterward it became "jpolitz:Hello\n yash:How are you". The port number stayed same because we are still in the same port.

Part 2:
