

###Project Title###

                                My Book List
  My Book list is simple application. We can use this application
  to add /remove book from a list.I used java script, HTML and CSS
  to make this application work.
                                  
  ###Represent the book###
      added the book into book list by entering title of the book
      Author of the book and Isbn number of the book
      when we enter the information in provided field and click add book
      button.
         1. constructor is a method that Iniatiated

  ###Remove the book###
  Remove the book from the list is click the X button next to the Isbn number
  // Book Class
    created a book class. It represent the a book and Inatiated the book class
    

    //User Interface UI
        UI handles Tasks.Using this we can remore,dispaly and show an Alert
        we loop the methosd to add the book to the list

        example:
         class UI {
  static displayBooks() {
          const books = Store.getBooks();

           books.forEach((book) => UI.addBookToList(book));
  }
         }



    // Store class
  Local Storage is used to store the book.Used the store class to store the book. Which means added book automatically stored in the 
      browser's local storage.

        // Events 

        Dispaly the book.Add the book and remove the book.

        Display Book:

        document.addEventListener('DOMContentLoaded', UI.displayBooks);


        Added the book:

        document.querySelector('#book-form').addEventListener('submit', (e) => {
        });
            e.preventDefault();

     
      Research:1

          used W3 School website to better understand concepts such as appendChild , querySelect , etc..
  https://www.w3schools.com/jsref/met_node_appendchild.asp

  w3schools.comw3schools.com
  HTML DOM Element appendChild() Method
  W3Schools offers free online tutorials, references and exercises in all the major languages of the web. Covering popular subjects like HTML, CSS, JavaScript, Python, SQL, Java, and many, many more.

  Research 2:
    
     Freecode camp helps to understand concepts more 

     https://www.freecodecamp.org/news/what-is-the-dom-document-object-model-meaning-in-javascript/