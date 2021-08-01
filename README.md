# WishlistFinal
CEN 4010 /// Final Project

# WishlistFinal

WishlistFinal is a Java library that focuses on the creation of a wishlist and updating to a MYSQL database. 

Features include:
- Ability to create a wishlist of books that belongs to user and has a unique name
- Ability add a book to a user’s wishlist
- Ability remove a book from a user’s wishlist into the user’s shopping cart
- Ability list the book’s in a user’s wishlist


## Usage

# localhost:8080/wishList/{userId}
Will grab the UserId and find the corresponding Wishlist and respond/print the userid, the wishid, the books and the wishlist name to the user or individual.

# localhost:8080/wishList
Will create a wishlist inputting the needed information from the constructor which includes:

    private List<String> books;
    private String wishlistName;
    private int id;
    private String userId;


# localhost:8080/wishList/add/{id}/{bookname}
Will add a book from the Wishlist when one inputs the wishid and the book name in addition will check if the book already does exist in the wishlist and if it does it will proceed to give error.

# localhost:8080/wishList/delete/{id}/{bookname}
Will delete a book from the Wishlist when one inputs the wishid and the book name in addition it will go ahead and add the book over to the User's shopping cart.


## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

